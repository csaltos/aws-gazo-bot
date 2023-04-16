# AWS Gazo bot

Scripts to create, customize and upload AWS images to the cloud

Based on the scripts created by Antoine Jacoutot at https://github.com/ajacoutot/aws-openbsd

## Requirements

* An AWS account with IAM roles management and EC2 access

* A Linux machine like Debian, Ubuntu, RedHat, Fedora or compatible

* An OpenBSD machine 7.2+ with SSH access

## Requirements for the Linux machine

* qemu (with arm and aarch64 support)
* libvirt
* awscli

## Requirements for the OpenBSD machine

* bash
* vmdktools
* awscli
