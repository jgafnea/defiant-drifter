# defiant-drifter

POC showing how OpenSCAP is used to assess compliance

## Overview

OpenSCAP is a security tool used to assess compliance with various security policies, like PCI-DSS. Typically, OpenSCAP is installed and executed directly on the target being checked. Here, the target is a CentOS VM created using Vagrant and Ansible, with Ansible also being used to install the tool and perform the check.

## Usage

Requires Vagrant

```sh
git clone https://github.com/jgafnea/defiant-drifter && cd defiant-drifter
make
```
