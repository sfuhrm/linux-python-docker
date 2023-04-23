# Linux Python Docker Image

[![Docker](https://github.com/sfuhrm/linux-python-docker/actions/workflows/docker.yml/badge.svg)](https://github.com/sfuhrm/linux-python-docker/actions/workflows/docker.yml)
![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/stephanfuhrmannionos/linux-python-docker)
![GitHub](https://img.shields.io/github/license/sfuhrm/linux-python-docker)

Github actions build infrastructure to matrix-build
several versions of Linux Distributions
with their default Python interpreter.

## Where you can find more

* The github repository [linux-python-docker](https://github.com/sfuhrm/linux-python-docker).
* The Docker image repository [stephanfuhrmannionos/linux-python-docker](https://hub.docker.com/r/stephanfuhrmannionos/linux-python-docker).

## Motivation for the repository

The repository exists to test-drive Ansible Molecule without
the need of letting Molecule build its own python-enabled Docker
images which is a time consuming process.

## How to use

Just log in to docker and type

```bash
docker pull docker.io/stephanfuhrmannionos/linux-python-docker:$TAG
```

For the valid tags, see below or at [Docker Hub](https://hub.docker.com/r/stephanfuhrmannionos/linux-python-docker).

## Supported tags

| Tag | Base Image | Dist Package | Python Version |
|-----|------------|--------------|----------------|
| debian-bookworm | debian:bookworm | python3 | Python 3.11.2 |
| debian-bullseye | debian:bullseye | python3 | Python 3.9.2 |
| debian-buster | debian:buster | python3 | Python 3.7.3 |
| debian-stretch | debian:stretch | python3 | Python 3.5.3 |
| fedora-36 | fedora:36 | python | Python 3.10.10 |
| fedora-37 | fedora:37 | python | Python 3.11.3 |
| fedora-38 | fedora:38 | python | Python 3.11.2 |
| fedora-39 | fedora:39 | python | Python 3.11.3 |
| oraclelinux-7 | oraclelinux:7 | python | Python 2.7.5 |
| oraclelinux-8 | oraclelinux:8 | python39 | Python 3.9.13 |
| oraclelinux-9 | oraclelinux:9 | python39 | Python 3.9.14 |
| ubuntu-bionic | ubuntu:bionic | python3 | Python 3.6.9 |
| ubuntu-focal | ubuntu:focal | python3 | Python 3.8.10 |
| ubuntu-jammy | ubuntu:jammy | python3 | Python 3.10.6 |
| ubuntu-kinetic | ubuntu:kinetic | python3 | Python 3.10.7 |
| ubuntu-lunar | ubuntu:lunar | python3 | Python 3.11.2 |

## License

This software is licensed under the [Apache 2.0](LICENSE.txt) license.
