# defiant-drifter

POC showing how OpenSCAP is used to assess compliance

## Overview

OpenSCAP is a security tool used to assess policy compliance with standards like HIPAA, PCI-DSS, and SOC 2. Typically, OpenSCAP is installed and run on the target being checked. Here, the target is a CentOS machine prepared using Vagrant. Ansible is used to install the tool and perform the scan. Results are saved to report.html.

## Usage

1. Install `vagrant`
2. Clone project
3. Run `make`

## Non-usage

1. View the included [report.html](https://github.com/jgafnea/defiant-drifter/blob/main/report.html)
