Ansible-Role Vector test

'vector_version' -subj


## example playbook:
```
- name: install vector
  hosts:
    - example_host
  become: true
  roles:
    - role: vector``` 
