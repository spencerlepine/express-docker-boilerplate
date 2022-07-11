# My Cool Project

[![CI](https://github.com/GITHUB_USERNAME/REPO_NAME/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GITHUB_USERNAME/REPO_NAME/actions/workflows/ci.yml) [![Publish Docker](https://github.com/GITHUB_USERNAME/REPO_NAME/actions/workflows/publish-to-ghcr.yml/badge.svg?branch=main)](https://github.com/GITHUB_USERNAME/REPO_NAME/actions/workflows/publish-to-ghcr.yml)[![Stable Version](https://img.shields.io/github/v/tag/GITHUB_USERNAME/REPO_NAME)](https://img.shields.io/github/v/tag/GITHUB_USERNAME/REPO_NAME) [![Latest Release](https://img.shields.io/github/v/release/GITHUB_USERNAME/REPO_NAME?color=%233D9970)](https://img.shields.io/github/v/tag/GITHUB_USERNAME/REPO_NAME?color=%233D9970)

NodeJS, Express, and Docker Boilerplate. CI/CD using GitHub Actions. Published to GitHub Container Registry.
## Setup
```sh
$ git clone https://github.com/GITHUB_USERNAME/REPO_NAME.git
$ cd REPO_NAME
$ docker-compose up -d
# access on localhost:3000
```

![Diagram](./diagram.png)

## Test
```sh
$ docker-compose exec api yarn run test
```

## Pull from GitHub Repository Container Registry
```sh
# docker pull ghcr.io/OWNER/IMAGE_NAME
$ docker pull ghcr.io/GITHUB_USERNAME/REPO_NAME:0.1.0
```
