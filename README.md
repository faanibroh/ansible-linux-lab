# Ansible Linux Lab

A hands-on Ansible automation project focused on professional role-based configuration management and CI validation.

## Project Goals

- Learn Ansible automation fundamentals
- Build reusable Ansible roles
- Manage Linux servers using Ansible
- Practice inventories and variables
- Use handlers, templates, defaults, and metadata
- Validate Ansible code with GitHub Actions
- Learn Ansible collections and Galaxy
- Prepare for Ansible Automation Platform (AAP)

## Architecture

```text
GitHub
   |
   v
GitHub Actions
   +-- YAML validation
   +-- Ansible syntax check
   +-- ansible-lint
   |
   v
Ansible Controller
   |
   v
AWS Linux Managed Node
