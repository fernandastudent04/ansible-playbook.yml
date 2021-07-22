# ansible-playbook.yml
---
- hosts: all
  vars:
    - testvar01: "Ola"
  tasks:
    - name: Debug
      debug:
        var: testvar01
