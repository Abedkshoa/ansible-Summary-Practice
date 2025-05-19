📘 Project Overview
This Ansible-based project is a practice exercise designed to reinforce foundational automation skills. It demonstrates how to configure a basic Ansible environment to perform simple remote tasks using modules like copy and shell.

The goal is to create and run a shell script across all defined hosts using Ansible. The project consists of:

- Setting up an ansible.cfg file to define Ansible behavior.

- Creating an hosts.ini inventory targeting local or remote machines.

- Writing a playbook.yaml that:

   - Copies a "Hello, World!" shell script to /tmp/hello.sh on each target.

   - Makes the script executable.

   - Executes the script and returns the output.

This exercise helps build confidence with basic Ansible syntax, inventory configuration, and module usage in a practical, repeatable way.
