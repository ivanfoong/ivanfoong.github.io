---
title: "Setup dev env with devcontainer"
date: 2021-10-20T21:28:48+0800
draft: false
---

# Setup Development Environment with Devcontainer

## Why devcontainer
TBD
Setting up devcontainer with multiple other services in docker with docker-compose


## Setup
1. Install VSCode with `Remote - Containers` extension
1. Create `.devcontainer/library-scripts/common-debian.sh`
1. Create `.devcontainer/library-scripts/docker-debian.sh`
1. Create `.devcontainer/Dockerfile`
1. Create `.devcontainer/docker-compose.yml`
1. Create `.devcontainer/devcontainer.json`

## Usage
Start devcontainer via <https://code.visualstudio.com/docs/remote/containers#_quick-start-openan-existing-folder-in-a-container>
After a while the devcontainer should have been build and ready to start developing
