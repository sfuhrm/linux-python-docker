# Linux Python Docker Container

Github actions build infrastructure to matrix-build
several versions of Linux Distributions
with their default Python interpreter.

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

| Tag |
|-----|
| debian-stretch |
| debian-buster |
| debian-bullseye |
| debian-bookworm |
| ubuntu-bionic |
| ubuntu-focal |
| ubuntu-jammy |
| ubuntu-kinetic |
| ubuntu-lunar |
| fedora-36 |
| fedora-37 |
| fedora-38 |
| fedora-39 |
| oraclelinux-9 |
| oraclelinux-8 |
| oraclelinux-7 |
| oraclelinux-6 |

## License

This software is licensed under the [Apache 2.0](LICENSE.txt) license.
