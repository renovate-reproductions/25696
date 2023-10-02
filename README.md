# renovate-ansible-galaxy-reprod

Mimimal reproduction for https://github.com/renovatebot/renovate/discussions/24937

Expected behaviour: Renovate resolves Ansible Galaxy dependencies.

Current behvaiour: Renovate fails to resolve Ansible Galaxy deps, see [renovate.log](renovate.log). Most likely due to a new version of Ansible Galaxy going live with a [new API version](https://ansible.readthedocs.io/projects/galaxy-ng/en/latest/community/api_v3/)?
