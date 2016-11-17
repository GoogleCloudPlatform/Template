# Markdown Templates for Google Cloud Platform Samples

The `.mdpp` files in this directory are templates used in READMEs relating to
Google Cloud samples.

## Before you begin

Install [MarkdownPP](https://github.com/jreese/markdown-pp), a preprocessor for
Markdown files. (Requires Python and PIP)

    pip install MarkdownPP

## Rendering the templates

    for readme in **/README.mdpp; do
      (
        cd $(dirname "$readme")
        markdown-pp README.mdpp -o README.md
      )
    done

