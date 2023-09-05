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

**Detailed documentation**

https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/creating_and_consuming_execution_environments/assembly-using-builder

