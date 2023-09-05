# AnsibleBuilderExample

**Prerequisites**

Install ansible-builder via dnf or pip

**To build a container** 

From this git repo directory run: 

```shell 
ansible-builder build
```

You can then see the container via podman image list:

```shell
localhost/ansible-execution-env   latest      c7016d7140c7  18 seconds ago      337 MB
```