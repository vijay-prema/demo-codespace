# Stencila VSCode Extension Demo

This demo creates a prepared Dockerized environment for testing Stencila, Stencila VSCode and Stencila Cloud without any changes to your workstation's environment. Stencila can also run locally by simply installing the [Stencila VSCode extension](https://marketplace.visualstudio.com/items?itemName=stencila.stencila) in VSCode. The demo environment described below is an alternative available for those who do not want to install VSCode, but want to test out Stencila and Stencila Cloud. 

## Two ways to run : 

### 1. Launching the demo in the Cloud (EASY!)

Our free tier will let you experiment with Stencila and try out our walkthroughs, or test on your own documents.

You can launch the demo, in a data center near you, by clicking this button:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/stencila/demo-codespace?quickstart=1)


### 2. Launching the demo Locally using Docker and Dev Container (more steps)
<details>
<summary>Expand to see Instructions</summary>

This repository has a [Dev Container](https://containers.dev/) defined in the `.devcontainer` directory of the repository. This defines a container that can run Stencila and the associated Stencila VSCode extension on your local machine in a containerized environment. To run locally (requires Docker). 

1. Install VSCode or have it already installed
2. Install Docker or have it already installed
3. Install the [Dev Container Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) in VSCode
4. `git clone https://github.com/stencila/demo-codespace`

</details>

## Interactive walkthroughs

When the Codespace is open we recommend trying one of our interactive walkthroughs. Press <kbd>F2</kbd> to bring up the Stencila command palette and select from one of the walkthroughs.


## Installed languages and packages

This Codespace includes Python and R with popular data science packages installed:

- Python: `numpy`, `matplotlib`, `pandas`, `requests`

- R: `tidyverse`

If you think we should add other languages or packages [create an issue](https://github.com/stencila/demo-codespace/issues/new), or submit a PR with changes to the [Dockerfile](https://github.com/stencila/demo-codespace/edit/main/.devcontainer/Dockerfile).

## Customizing the Codespace

You can [create a fork](https://github.com/stencila/demo-codespace/fork) of this repository and modify the following files to customize the environment:

- add language runtimes and packages to `.devcontainer/Dockerfile`

- add VSCode extensions to `.devcontainer/devcontainer.json`

We are [planning](https://github.com/stencila/demo-codespace/issues/3) to make it easier to fork and customize this repository in the future.


5. `cd demo-codespace`
6. `code .`
7. Chose "Reopen in Container from the pop-up in VSCode"

<img width="531" alt="image" src="https://github.com/user-attachments/assets/89d3da21-bd54-4129-94e6-506889cc9534">
