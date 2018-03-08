## Project Name

![status: inactive](https://img.shields.io/badge/status-inactive-red.svg)

This project is no longer actively developed or maintained.

Review the [release preparing](https://opensource.google.com/docs/releasing/preparing/)
document instead.

Project description.

See our other [Google Cloud Platform github
repos](https://github.com/GoogleCloudPlatform) for sample applications and
scaffolding for other frameworks and use cases.

## Getting the sample code

Get the latest sample code from GitHub using Git or download the repository as a ZIP file.
([Download](https://github.com/GoogleCloudPlatform/REPO_NAME/archive/master.zip))

    git clone https://github.com/GoogleCloudPlatform/REPO_NAME.git


## Before you begin

1.  Download and install the [Google Cloud
    SDK](https://cloud.google.com/sdk/docs/), which includes the
    [gcloud](https://cloud.google.com/sdk/gcloud/) command-line tool.

1.  Create a [new Google Cloud Platform project from the Cloud
    Console](https://console.cloud.google.com/project) or use an existing one.

1.  Initialize the Cloud SDK.

        gcloud init


## Run Locally

You don't need a valid project ID to run locally, but will need a valid ID to
deploy.

1. Run the application using the tool of your choice.  

1. Visit the application at [http://localhost:8080](http://localhost:8080).

## Deploying

1.  Use the [Cloud Console](https://console.cloud.google.com/project)  to create
    a project ID.

1.  Configure gcloud with your project ID.

        gcloud config set project YOUR-PROJECT-ID

1.  Use gcloud to deploy your app.

        gcloud app deploy REPO_NAME/

1.  Congratulations!  Your application is now live at
    your-project-id.appspot.com

## Contributing changes

* See [CONTRIBUTING.md](CONTRIBUTING.md)

## Licensing

* See [LICENSE](LICENSE)
