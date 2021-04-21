# Workstation Playbooks
This repo contains ansible playbooks that I use to bootstrap new system installations.

Due to personal preference, the majority of these playbooks were written with Fedora Linux in mind.

## Prerequisites
Make sure you have `ansible` and `ansible-galaxy` installed.

Run the following command before running the playbooks.
```bash
$ ansible-galaxy collection install -r requirements.yml
```
