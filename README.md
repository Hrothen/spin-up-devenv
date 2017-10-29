Ansible playbook to spin up a dev environment on a fresh Arch install

## Usage

First make sure all installed packages are up to date

`pacman -Syu`

Then run `ansible-playbook --ask-sudo-pass site.yml` and answer the prompts.
