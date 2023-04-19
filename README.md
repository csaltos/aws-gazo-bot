# AWS Gazo bot

> **DISCLAIMER**: This is a work in progress, I'm trying to create OpenBSD images from Linux, specially using arm64 and riscv64 for AWS since OpenBSD has no vmm support for arm64 nor riscv64 yet.

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
