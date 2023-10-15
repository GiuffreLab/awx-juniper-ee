# Ansible AWX-Operator Juniper Execution Environment

This is a repo to build an Ansible Execution Environment that can communicate with Juniper devices using the `juniper.junos` roles as well as the `juniper.devices` collection.

it will work with the following `roles` or `collections` commands

`juniper.junos`
`Juniper.junos`
`juniper.device`

The compiled version of this is hosted on docker hub [Check Here](https://hub.docker.com/r/giuffrelab/awx-juniper-ee) and can be used directly in your AWX environment.

If you wish to learn how to build Execution Environments, [Check Here](https://github.com/GiuffreLab/building-execution-environments).

**Add the new Execution Environment**

change `giuffrelab` and the image name you chose to whatever you used

Under `Administration` and `Execution Environments`
- Select `Add`
- Fill out the `name` field
- Under Pull select `Always Pull`
- Under image put `giuffrelab/awx-juniper-ee:latest`
- Under `Registry credential` select the one created above
- `Save`
