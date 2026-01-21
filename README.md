# deployer-ibm-quarkus

Deployer automations for https://techzone.ibm.com/collection/ibm-quarkus

Use `oc login`, then run the ansible playbook:

```
ansible-playbook site.yml
```

For advanced workshop content:
```
ansible-playbook site.yml -e advanced_workshop_enabled=true
```
