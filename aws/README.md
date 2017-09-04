# Using Terraform with AWS

This directory contains a number of subdirectories with example configurations intended to help users understand how to use Terraform ([http://terraform.io](http://terraform.io)) with AWS. All of these example configurations require a working Terraform installation and access to a valid AWS account.

## Contents

* **bastion-aws**: This directory contains a Terraform configuration to create a topology for using an SSH bastion host. It creates a publicly accessible instance to serve as the bastion, and a private instance that can only be reached through the bastion.

* **new-vpc**: This directory contains a Terraform configuration to create a new VPC and associated items, then turn up a CoreOS instance in that VPC. _This directory requires Terraform 0.7.9 or later._

* **README.md**: This file you're currently reading.

* **simple-ec2**: This directory contains a simple Terraform configuration for spinning up an Ubuntu 14.04 EC2 instance in an account's default VPC.

* **simple-module**: This directory contains a very simple example of using a Terraform module for more reusable code blocks.

## Prerequisites

These instructions assume you've already installed Terraform and that you have access to a valid AWS account. Installing Terraform and/or working with AWS accounts are not covered in any of these materials.

These environments were tested with Terraform 0.7.7 and later. Earlier versions may or may not work; I recommend upgrading your version of Terraform to 0.7.7.

## License

This material is licensed under the MIT License.
