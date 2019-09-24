# BoxSkillet
Skillet for securing Box with the Palo Alto Networks Security Operating Platform

### Overview
Palo Alto Networks created Skillets to simplify the implementation of best practices associated with the Security 
Operating Platform.  This Skillet implements the configuration steps listed in the 
[Deployment Guide for Securing Box](https://www.paloaltonetworks.com/resources/guides/securing-box-deployment-guide).
This includes controls for the following Box functions:
- Box base
- Distinguish between Box Enterprise and Consumer traffic
- Uploading of files
- Downloading of files
- File management controls such as renaming or creating files and folders
- File sharing

The Skillet files are loaded into the Panhandler tool to provide a web interface to prompt for necessary input and run 
on a desired endpoint.  Please review the [Running Panhandler](https://panhandler.readthedocs.io/en/latest/running.html) 
guide for details on installing and starting Panhandler.

Please see [Installing Box Skillet](docs/install.md) and [Using Box Skillet](docs/usage.md) for instructions 
regarding this Skillet.

### Assumptions and Prerequisites

- Access to the [Panhandler](https://panhandler.readthedocs.io/en/latest/) tool.
- The PAN-OS and Panorama versions tested with this Skillet are 8.1 and 9.0.
- Firewalls must be operational. This Skillet only covers the policy specific to Box and not the
deployment of the firewalls.
- DNS resolution is a requirement for the Box rules to function correctly and is expected to be configured.
- For optimal results SSL Decryption should be configured.