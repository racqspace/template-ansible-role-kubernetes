# Cookiecutter Template: ansible-role-kubernetes

![MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/racqspace/template-ansible-role-kubernetes/Main?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/racqspace/template-ansible-role-kubernetes?style=flat-square)
![GitHub Release Date](https://img.shields.io/github/release-date/racqspace/template-ansible-role-kubernetes?style=flat-square)
![Maintenance](https://img.shields.io/maintenance/yes/2022?style=flat-square)

Create the folder structure and basic functionality to develop an ansible role that targets kubernetes workload.

## Template Variables

Variable Name | Default Value | Description
------------ | ------------- | -------------
author | Mr Kubernetes | Set author in meta/main.yml
description | Ansible Role Description |  Set description in meta/main.yml.
license | MIT | Set license in meta/main.yml.
min_ansible_version | 2.10  | Set min_ansible_version in meta/main.yml.
namespace | role_namespace |  Set namespace in meta/main.yml.
role_name | my_role_name | Set Ansible role name used throughout the template.

## Template Examples

1. Install cookiecutter on your system

```
pip3 install -r requirements.txt
```

2. Run cookiecutter

```
cookicutter https://github.com/racqspace/template-ansible-role-kubernetes
```

3. Answer the cookiecutter questionair.

```
author [Mr Kubernetes]: 
description [Ansible Role Description]: 
license [MIT]: 
min_ansible_version [2.10]: 
namespace [role_namespace]: 
role_name [my_role_name]: 
```

4. Cookiecutter will create a new folder named after `role_name` containing your new ansible role folder structure.

## License

MIT

## Author Information

This cookiecutter template was created in 2021 by [Clemens Kaserer](https://www.ckaserer.dev/).

Contributions by:

- [@ckaserer](https://github.com/ckaserer)
