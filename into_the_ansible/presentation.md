title: Into The Ansible
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  {{title}}
]

---

class: impact

# {{title}}
## Jacob Hudson - SpotHero - 4/3/2019

---

# Who am I?

### Lead Cloud Engineer - Advanced Analytics @ Discover
- 1/2019 - Now
- Mostly Ansible, with some Terraform, Python, Linux

### Software Engineer II - Site Reliability Engineering @ Grainger
- 6/2015-1/2019
- Ansible, Splunk, Python, Linux

### Network Technician @ University Housing - University of Illinois
- 8/2012-5/2015
- Networking, Linux, so on...

---

class: impact

# The Basics
## Features of Ansible and Key Terms

---

# What is Ansible?

- Python based
- Agentless
- Defaults to push-based operation
- Opensource
- Centralizaton via Tower
- Enterprise Support

---

# Modes of Operations

## Adhoc

```bash
ansible all -m ping
```

## Through Playbooks
- Playbooks are series of tasks, like below
  ```
  - name: Sleep for 15 seconds
    command: sleep 15
  ```
- Playbooks are series of plays to achieve a goal
- Think of them like functions

---

# (Facts), Conditionals, and Loops

### Facts
- Can store values set by users, previous plays, or received from a system
- All common types exist: ints, floats, bools, strings, etc
- Similar to assignment in Python, except done using `set_fact`

### Conditionals
- `when` in Ansible
- Identical to an `if` state in Python

### Loops
- For Loops and While loops both exist
- The docs have many good examples

---

# Roles

## Entirely reusable Playbook
- Very modular
- Think of it like a class in Python

---

class: impact

# Use Cases
## How has it been used

---

# How it is used

## Provisioning
- Building infrastructure, eg AWS services
- Terraform

## Configuration Management
- Installing/upgrading/etc on a large free of machines at once
- Chef/Puppet/Salt

---

# Self Service
- Allowing a user a limited subset of actions
- Fully monitored
- Allows for UI-based interaction
- Ansible Tower
- Open Source Variants:  AWX and Semaphore

---

class: impact

# Gotchas and Pitfalls
## DevOps Engageemnt or DevOops enragement?

---

# Spacing

---

# Path Selection

---

# Security

---

class: impact

# Resources
## How to get started on your Pythonic DevOps journey!
