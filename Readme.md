#### Import the module in your recipe

```
terraform get
```

#### Generate your keys

* use : http://generator.my-addr.com/generate_ssh_public_rsa_key-private_rsa_key-ssh_pair_online_tool.php
* create data/k8s.private.key.data
* create data/k8s.public.key.data

### Apply changes

```
terraform apply
```

#### Users by instance type

| OS/Distro         | User                        |
| ---------------- |:-----------------------------:|
| Amazon Linux      | ec2-user|
| Ubuntu | ubuntu |
| RHEL 6.4 | aec2-user |
| RHEL 6.3 | root |
| FreeBSD | ec2-user |
| SUSE | root |
| Fedora | fedora |
| Centos | centos |