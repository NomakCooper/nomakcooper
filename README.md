## Hi there 👋
#### is it time? :thinking:

```yaml
---
- name: Life Module
  hosts: localhost
  become: true
  become_method: sudo

# global vars
  vars:
    name: 'Marco'
    alias: 'Nocchia'
    username: 'NomakCooper'
    country: 'Italy'
    role: 'Diagnostic Operator'

  # pre setup
  pre_tasks:

  - name: setup filter
    setup:
      filter:
      - 'wokeup_date_time'
      - 'sleep_hours'
      - 'number_coffees'

  tasks:

  # chek day
  - name: Check woke up time
    fail:
      msg: sorry it's too early!
    when: wokeup_date_time.hours|int < 12

  - name: Check sleep
    fail:
      msg: sorry it's not time yet
    when: sleep_hours|int < 8

  - name: Check coffee
    fail:
      msg: sorry but the first coffee is sacred
    when: number_coffees|int < 1

  - name: it's time
    debug:
      msg: "{{name}} is ready for a new day" 
```

<!--
**NomakCooper/nomakcooper** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

