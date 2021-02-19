<h1 align="center">
	<a href="https://github.com/WolfSoftware">
		<img src="https://raw.githubusercontent.com/WolfSoftware/branding/master/images/general/banners/64/black-and-white.png" alt="Wolf Software Logo" />
	</a>
	<br>
	Docker containers with tgenv installed
</h1>

<p align="center">
	<a href="https://travis-ci.com/DockerToolbox/tgenv">
		<img src="https://img.shields.io/travis/com/DockerToolbox/tgenv/master?style=for-the-badge&logo=travis" alt="Build Status">
	</a>
	<a href="https://github.com/DockerToolbox/tgenv/releases/latest">
		<img src="https://img.shields.io/github/v/release/DockerToolbox/tgenv?color=blue&style=for-the-badge&logo=github&logoColor=white&label=Latest%20Release" alt="Release">
	</a>
	<a href="https://github.com/DockerToolbox/tgenv/releases/latest">
		<img src="https://img.shields.io/github/commits-since/DockerToolbox/tgenv/latest.svg?color=blue&style=for-the-badge&logo=github&logoColor=white" alt="Commits since release">
	</a>
	<a href="LICENSE.md">
		<img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Software License">
	</a>
	<br>
	<a href=".github/CODE_OF_CONDUCT.md">
		<img src="https://img.shields.io/badge/Code%20of%20Conduct-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/CONTRIBUTING.md">
		<img src="https://img.shields.io/badge/Contributing-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/SECURITY.md">
		<img src="https://img.shields.io/badge/Report%20Security%20Concern-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/SUPPORT.md">
		<img src="https://img.shields.io/badge/Get%20Support-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
</p>

## Overview

This is a selection of Docker containers preinstalled with [tgenv](https://github.com/cunymatthieu/tgenv) so that you can use any version of [Terragrunt](https://terragrunt.gruntwork.io/) you want, or even install multiple versions.

We try to offer as many operating system flavours as possible, but we only use currently supported versions of each one.

| Dockerfile | Docker Hub Repo | Docker Hub Tags |
| --- | --- | --- |
| [Alpine Linux 3.10](Dockerfiles/alpine/3.10/Dockerfile)             | [wolfsoftwareltd/tgenv-alpine](https://hub.docker.com/r/wolfsoftwareltd/tgenv-alpine)           | 3.10                        |
| [Alpine Linux 3.11](Dockerfiles/alpine/3.11/Dockerfile)             | [wolfsoftwareltd/tgenv-alpine](https://hub.docker.com/r/wolfsoftwareltd/tgenv-alpine)           | 3.11                        |
| [Alpine Linux 3.12](Dockerfiles/alpine/3.12/Dockerfile)             | [wolfsoftwareltd/tgenv-alpine](https://hub.docker.com/r/wolfsoftwareltd/tgenv-alpine)           | 3.12                        |
| [Alpine Linux 3.13](Dockerfiles/alpine/3.13/Dockerfile)             | [wolfsoftwareltd/tgenv-alpine](https://hub.docker.com/r/wolfsoftwareltd/tgenv-alpine)           | 3.13, latest                |
| [Amazon Linux 1](Dockerfiles/amazonlinux/1/Dockerfile)              | [wolfsoftwareltd/tgenv-amazonlinux](https://hub.docker.com/r/wolfsoftwareltd/tgenv-amazonlinux) | 1                           |
| [Amazon Linux 2](Dockerfiles/amazonlinux/2/Dockerfile)              | [wolfsoftwareltd/tgenv-amazonlinux](https://hub.docker.com/r/wolfsoftwareltd/tgenv-amazonlinux) | 2, latest                   |
| [Centos 7](Dockerfiles/centos/7/Dockerfile)                         | [wolfsoftwareltd/tgenv-centos](https://hub.docker.com/r/wolfsoftwareltd/tgenv-centos)           | 7,                          |
| [Centos 8](Dockerfiles/centos/8/Dockerfile)                         | [wolfsoftwareltd/tgenv-centos](https://hub.docker.com/r/wolfsoftwareltd/tgenv-centos)           | 8, latest                   |
| [Debian 9 (Stretch)](Dockerfiles/debian/9/Dockerfile)               | [wolfsoftwareltd/tgenv-debian](https://hub.docker.com/r/wolfsoftwareltd/tgenv-debian)           | 9, stretch                  |
| [Debian 9 (Stretch Slim)](Dockerfiles/debian/9-slim/Dockerfile)     | [wolfsoftwareltd/tgenv-debian](https://hub.docker.com/r/wolfsoftwareltd/tgenv-debian)           | 9-slim, stretch-slim        |
| [Debian 10 (Buster)](Dockerfiles/debian/10/Dockerfile)              | [wolfsoftwareltd/tgenv-debian](https://hub.docker.com/r/wolfsoftwareltd/tgenv-debian)           | 10, buster, latest          |
| [Debian 10 (Buster Slim)](Dockerfiles/debian/10-slim/Dockerfile)    | [wolfsoftwareltd/tgenv-debian](https://hub.docker.com/r/wolfsoftwareltd/tgenv-debian)           | 10-slim, buster-slim        |
| [Debian 11 (Bullseye)](Dockerfiles/debian/11/Dockerfile)            | [wolfsoftwareltd/tgenv-centos](https://hub.docker.com/r/wolfsoftwareltd/tgenv-centos)           | 11, bullseye                |
| [Debian 11 (Bullseye Slim)](Dockerfiles/debian/11-slim/Dockerfile)  | [wolfsoftwareltd/tgenv-debian](https://hub.docker.com/r/wolfsoftwareltd/tgenv-debian)           | 11-slim, bullseye-slim      |
| [Ubuntu 16.04 (Xenial Xerus)](Dockerfiles/ubuntu/16.04/Dockerfile)  | [wolfsoftwareltd/tgenv-ubuntu](https://hub.docker.com/r/wolfsoftwareltd/tgenv-ubuntu)           | 16.04, xenial               |
| [Ubuntu 18.04 (Bionic Beaver)](Dockerfiles/ubuntu/18.04/Dockerfile) | [wolfsoftwareltd/tgenv-ubuntu](https://hub.docker.com/r/wolfsoftwareltd/tgenv-ubuntu)           | 18.04, bionic               |
| [Ubuntu 20.04 (Focal Fossa)](Dockerfiles/ubuntu/20.04/Dockerfile)   | [wolfsoftwareltd/tgenv-ubuntu](https://hub.docker.com/r/wolfsoftwareltd/tgenv-ubuntu)           | 20.04, focal, latest        |

> Debian bullseye isn't technically Debian 11 (yet)

## Naming convention

### Local containers

```
  tgenv-<os>-<version> e.g. tgenv-debian-10
```

### Published containers

```
  wolfsoftwareltd/tgenv-<os>:<version> e.g. wolfsoftwareltd/tgenv-debian:10
```

## Contributors

<p>
	<a href="https://github.com/TGWolf">
		<img src="https://img.shields.io/badge/Wolf-black?style=for-the-badge" />
	</a>
</p>

## Show Support

<p>
	<a href="https://ko-fi.com/wolfsoftware">
		<img src="https://img.shields.io/badge/Ko%20Fi-blue?style=for-the-badge&logo=ko-fi&logoColor=white" />
	</a>
</p>
