# roles/singularity/README.md

[![Build Status](https://travis-ci.org/cjsteel/singularity.svg?branch=master)](https://travis-ci.org/cjsteel/singularity)
[![Travis CI](http://img.shields.io/travis/csteel/singularity/default.svg?style=flat)](http://travis-ci.org/csteel/singularity/default)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)

## Description

singularity is an Ansible role used to  

## References

* https://www.sylabs.io/guides/2.5.1/user-guide/

## Recommended

Running Ansible in a virtual environment allows for a lot of testing flexibility.

* [docs/ansible-setup](docs/ansible-setup.md)

## Requirements

* Ansible

## Variables

### project_name/singularity.yml

* [example_playbook.yml](files/example_playbook.yml)

To install:

```shell
cd project_directory
cp roles/singularity/files/example_playbook.yml singularity.yml
# edit if required
nano singularity.yml
```

### project_name/site.yml

* [example_singularity.yml](files/example_site.yml)

From the projects main directory run the following:

```yaml
cp roles/singularity/files/example_playbook.yml singularity.yml
cat singularity.yml
```

### project/group_vars/all/project_defaults.yml

[files/group_vars/all/example_defaults.yml](files/group_vars/all/example_defaults.yml)

```yaml
cp roles/singularity/files/group_vars/all/example_defaults.yml group_vars/all/project_defaults.yml
cat group_vars/all/project_defaults.yml
```

## Testing

Move into the role directory and run vagrant:

```shell
cd roles/singularity
vagrant up
```

## Authors and Contributors

- [Christopher Steel](http://mcin-cnim.ca/) | [e-mail](mailto:christopher.steel@mcgill.ca)
- [John Le](http://mcin-cnim.ca/) | [e-mail](mailto:john.le@mcgill.ca)
- [Andy Teng](http://mcin-cnim.ca/) | [e-mail](xiaoqiu.teng@mcgill.ca)

## License

* ](https://tldrlegal.com/license/bsd-3-clause-license-(revised))

***
## Open Science

The Neuro has adopted the principles of Open Science. We are inspired by the likes of the Allen Institute for Brain Science, the National Institutes of Health's Human Connectome project, and the Human Genome project. For additional information, please see [Open Science at the Neuro](https://www.mcgill.ca/neuro/open-science-0).

![neuro](imgs/mcin-neuro-logo.png)

  

* ansible-role-singularity generated using [galaxy-role-skeleton](https://github.com/cjsteel/galaxy-role-skeleton)
