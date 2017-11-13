Ansible playbook to spin up a dev environment on a fresh Arch install

## Usage

First make sure all installed packages are up to date

`pacman -Syu`

Then run `ansible-playbook --ask-become-pass site.yml` and answer the prompts. Sometimes the AUR packages give an error,
but this seems to be spurious and running the playbook again works.
