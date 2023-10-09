# Docker Base Image for Distronode Linux
This repository contains all scripts and files needed to create a Docker base image for the Distronode Linux distribution.
## Dependencies
Install the following Distronode Linux packages:
* make
* devtools
* docker
## Usage
Run `make docker-image` as root to build the base image.
## Purpose
* Provide the Distronode experience in a Docker Image
* Provide the most simple but complete image to base every other upon
* `pacman` needs to work out of the box
* All installed packages have to be kept unmodified
