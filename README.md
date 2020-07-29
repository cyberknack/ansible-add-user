# ansible-add-user
Add or remove users and their public-key in linux(debian, redhat) remote hosts.  
To remove users and their public-key from remote host change the value of `state` and `remove` in `vars/users.yml`.  
```
state: absent
remove: true
```
# Requirements
None.
# Role Variables
see `vars/users.yml`
# Dependencies
None.
# Example Playbook
```
- host: all
  role:
   - ansible-add-user
```
# License
MIT

# Author Information
This role was created in 2020 by Saeed Ghasempoor.
