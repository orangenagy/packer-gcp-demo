# Initial setup

## Overview
This page outlines the steps to get to a stage where we can run packer in gcp. These will be manual / in the gui. Later we can run packer.

## Initial setup steps Steps
1. Create project
2. Create service account, download json file

## Packer run
1. Set application default credentials:
```export GOOGLE_APPLICATION_CREDENTIALS=<path_to_json>```
2. Run Packer
```packer build vm_image.json```
