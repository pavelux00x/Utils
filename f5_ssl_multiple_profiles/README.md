## UTILS


### Nodes
```yaml
- name: Force node offline
  bigip_node:
    state: disabled
    name: 10.20.30.40
    provider:
      server: lb.mydomain.com
      user: admin
      password: secret
```