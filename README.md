# Playbooks
[Ansible Playbooks](https://www.ansible.com/) for automating server configuration.

## Environment Details
* Python 3.7
* Ansible 2.7 (via `pip`)

## Execution
The playbooks should be executed using the [`run-ansible`](run-ansible)
script provided in the repo.

The script should be executed as such:

```shell
(ansible) $ ./run-ansible your-playbook-file.yaml
```

The script will perform a syntax check first and then execute if the
syntax check is successful.