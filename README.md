Ansible playbook

# Java Boilerplate Application Setup

This repository contains the necessary configuration to set up a Java Boilerplate Application using Ansible, Nginx, PostgreSQL, and other tools.

## Prerequisites

- Ansible installed on the control machine
- Access to the server with the necessary permissions
- SSH key setup for Ansible to access the server

## Files

- **inventory.cfg**: Ansible inventory file specifying the target hosts.
- **main.yaml**: Ansible playbook to set up the Java application and its dependencies.
- **nginx.conf.j2**: Jinja2 template for Nginx configuration.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/hngprojects/hng_boilerplate_java_web.git

