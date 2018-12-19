# packer-centos7

Initializes a blank Centos 7 VM image using Packer

**CentOS Version**: 7.5 (1804)

## Requirements

  - [Packer](http://www.packer.io/)
  - [VirtualBox](https://www.virtualbox.org/)

## Usage

Make sure all the required software (listed above) is installed, then cd to the directory containing this README.md file, and run:

    $ packer build packer.centos7.json
