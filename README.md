---
- hosts: all
  testvar01: Ola!
  tasks:
    - name: Print variable testvar01
      debug:
        var: testvar01
