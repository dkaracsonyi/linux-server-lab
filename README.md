# Linux Server Lab

My first Linux server administration lab.

## Hardware / VM

- Ubuntu Server
- 2 CPU
- 4 GB RAM
- 30 GB disk

## Goals

- Learn Linux administration
- Learn Git and GitHub
- Practice networking
- Practice SSH
- Practice services and logs
- Build a foundation for DevOps and cloud engineering

## What I configured
- I set up a Ubuntu Server VM over Oracle Virtualbox
- Set up the SSH, as well as SSH key pairs, although
- Set up Nginx
- Set up UFW firewall

## Problems encountered
- I'm still being asked to authenticate when SSHing to the VM

## 10. oct - 1st update
- I figured out what the issue was, the ownership of the authorized_keys has not been set up correctly, User had no access to the file. I can SSH without password now.

