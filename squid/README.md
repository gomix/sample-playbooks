# Squid Users
Simple Ansible Playbook to manage Squid authenticated users.

## Rules
1. Your Squid authenticates your users against local Linux users.
2. Your Squid verifies group membership using Linux groups.

## Data
squid-users-vars.yml file has users data, including passwords, then just be carefull if you this in production.
