# dbt-dev

Shell repo containing VS Code Dev Container configuration for dbt.

## Getting started

1. Install VS Code and the Dev Containers extension
1. This setup assumes a Postgresql backend as an example. Update `.devcontainer/requirements.txt` with your preferred backend name and version to suit your needs.
1. Follow the [instructions on setting up Git credential sharing](https://code.visualstudio.com/remote/advancedcontainers/sharing-git-credentials) with your VS Code dev container
1. When prompted, click **Reopen in Container**, or press `Command + Shift + P` and choose **Dev Containers: Reopen in Container**

You're all set. Create your new dbt project by running `dbt init my_project`
