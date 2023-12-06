# nephelaiio.k8s_repo

[![Build Status](https://github.com/nephelaiio/ansible-role-k8s-repo/actions/workflows/molecule.yml/badge.svg)](https://github.com/nephelaiio/ansible-role-k8s-repo/actions/wofklows/molecule.yml)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nephelaiio.k8s-repo.vim-blue.svg)](https://galaxy.ansible.com/nephelaiio/k8s-repo/)

An [ansible role](https://galaxy.ansible.com/nephelaiio/k8s-repo) to install and configure Kubernetes package repostiories

## Role Variables

Please refer to the [defaults file](/defaults/main.yml) for an up to date list of input parameters.

## Dependencies

By default this role does not depend on any external roles. If any such dependency is required please [add them](/meta/main.yml) according to [the documentation](http://docs.ansible.com/ansible/playbooks_roles.html#role-dependencies)

## Example Playbook

- hosts: servers
  roles:
     - role: nephelaiio.k8s_repo

## Testing

Please make sure your environment has [docker](https://www.docker.com) installed in order to run role validation tests. Additional python dependencies are listed in the [requirements file](https://github.com/nephelaiio/ansible-role-requirements/blob/master/requirements.txt)

Role is tested against the following distributions (docker images):

  * Ubuntu Jammy
  * Ubuntu Focal
  * Debian Bullseye
  * Debian Bookworm

You can test the role directly from sources using command ` molecule test `

## License

This project is licensed under the terms of the [MIT License](/LICENSE)
