# Cloud-Formation Project

## Built with
- YAML
- JSON
- Shell Scripts

## Description
You'll need to create a Launch Configuration for your application servers in order to deploy four servers, two located in each of your private subnets. The launch configuration will be used by an auto-scaling group.

## Instructions
- Below Command is for creating Stack
`./createStack.sh NameOfStack stack.yml parameters.json`

- Below Command is for update Stack
`./updateStack.sh NameOfStack stack.yml parameters.json`

Where you need to replace NameOfStack with the name you wanna give to your stack.
