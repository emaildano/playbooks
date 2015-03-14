```
ssh-add ~/.ssh/id_rsa ~/.ssh/keyname.pem
```

```
/etc/ansible/hosts
```

```
/etc/ansible/hosts --refresh-cache
```

```
ansible-playbook -i /etc/ansible/hosts launch.yml --check
```

```
ansible-playbook -l tag_Name_staging_dev -i /etc/ansible/hosts provision.yml
```

```
ansible-playbook -l tag_Name_staging_dev -i /etc/ansible/hosts secure-root.yml
```
