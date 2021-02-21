# Ansible Examples for multiple operations

* TBD AWS Ec2 instance
* TBD AWS Multiple HTTP and DB instances with LB 
* TBD - Azure simple instance


## Commands

- Install Plugins for Amazon AWS
```
ansible-galaxy collection install amazon.aws
```

- List all ec2 instances in eu-central-1 
```
ansible-inventory  -i _aws_ec2.yaml --list

```

