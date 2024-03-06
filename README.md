# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks Done
Created a CI pipeline in GitHub Actions with steps for linting and unit testing.

Used Tekton to create tasks for linting, unit testing, and building an image.

Created an OpenShift CI Pipeline that uses the previously created Tekton steps.

Added the deploy step to the OpenShift pipeline that deploys the code to the lab OpenShift cluster. You should complete all the work in the final project in this lab environment.

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
