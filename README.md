# get-lc-of-asg

Get Launch Configuration name of the desired Auto Scaling Group, it will return an asg_lc_name fact.


Role Variables
--------------

* `asg.name`   : Auto Scaling Group name
* `asg.region` : AWS region


Example Playbook
----------------

```yaml
- hosts: localhost
  connection: local
  gather_facts: no
  roles:
    - get-ami-of-autoscaling-group
```

License
-------

GPL

