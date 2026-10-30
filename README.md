# ci-cd-final-project

## Project: ci-cd-final-project

A production-ready CI/CD pipeline built for cloud-native applications featuring:
- Continuous Integration using GitHub Actions: Linting with flake8 and running unit tests with nose.
- OpenShift Tekton Pipelines with cleanup, git-clone, flake8, nose, buildah, and deploy tasks.
- Deployed application: cicd-app running on OpenShift.