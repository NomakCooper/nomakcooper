## Hi there 👋

![RedHat Linux][redhat-shield]
![Oracle Linux][oraclel-shield]
![Oracle Exadata][oraclee-shield]
![Oracle Solaris][oracles-shield]
![HP UX][hpux-shield]
![HP service guard][hpsg-shield]
![Veritas vcs][vcs-shield]
![Veritas sfha][sfha-shield]
![Vmware vsphere][vsphere-shield]
![google compute engine][gengine-shield]
![ansible][ansible-shield]
![AWX][awx-shield]
![GiLab][gitlab-shield]

![HTML][html-shield]
![CSS][css-shield]
![JS][js-shield]
![Python][py-shield]
![YAML][yaml-shield]
---

[redhat-shield]: https://img.shields.io/badge/redhat-enterprice%20linux-red?style=flat-square&logo=redhat&logoColor=red
[oraclel-shield]: https://img.shields.io/badge/oracle-linux-red?style=flat-square&logo=oracle&logoColor=red
[oraclee-shield]: https://img.shields.io/badge/oracle-exadata-red?style=flat-square&logo=oracle&logoColor=red
[oracles-shield]: https://img.shields.io/badge/oracle-solaris-red?style=flat-square&logo=oracle&logoColor=red
[hpux-shield]: https://img.shields.io/badge/hp-ux-blue?style=flat-square&logo=hp&logoColor=blue
[hpsg-shield]: https://img.shields.io/badge/hp-serviceguard-blue?style=flat-square&logo=hp&logoColor=blue
[vcs-shield]: https://img.shields.io/badge/veritas-vcs-red?style=flat-square&logo=veritas&logoColor=red
[sfha-shield]: https://img.shields.io/badge/veritas-storage%20foundation-red?style=flat-square&logo=veritas&logoColor=red
[vsphere-shield]: https://img.shields.io/badge/vmware-vsphere-blue?style=flat-square&logo=vmware&logoColor=blue
[gengine-shield]: https://img.shields.io/badge/-Google_Cloud_Platform-1a73e8?style=flat-square&logo=google-cloud&logoColor=white
[ansible-shield]: https://img.shields.io/badge/ansible-automation-red?style=flat-square&logo=ansible&logoColor=white
[awx-shield]: https://img.shields.io/badge/ansible-awx-blue?style=flat-square&logo=awx&logoColor=white
[gitlab-shield]: https://img.shields.io/badge/gitlab-555555?style=flat-square&logo=gitlab&logoColor=orange

[html-shield]: https://img.shields.io/badge/html-orange?style=flat-square&logo=html5&logoColor=white
[css-shield]: https://img.shields.io/badge/css-blue?style=flat-square&logo=css3&logoColor=white
[js-shield]: https://img.shields.io/badge/javascript-yellow?style=flat-square&logo=javascript&logoColor=white
[py-shield]: https://img.shields.io/badge/python-blue?style=flat-square&logo=python&logoColor=yellow
[yaml-shield]: https://img.shields.io/badge/yaml-red?style=flat-square&logo=yaml&logoColor=white

## last post: ✍️
![reddit][reddit-shield]

* **[ansible.builtin.service_facts new issue #84607 for incorrect state](https://www.reddit.com/r/ansible/comments/1i97f8w/ansiblebuiltinservice_facts_new_issue_84607_for/)** ⭐ _new_ ⭐
* **[AWX push notification card on Google Meet Spaces](https://www.reddit.com/r/ansible/comments/1i53v6p/awx_push_notification_card_on_google_meet_spaces/)**
* **[exa_facts module: Gathers facts from Oracle Exadata Machine](https://www.reddit.com/r/ansible/comments/1hxmkuc/exa_facts_module_gathers_facts_from_oracle/)**

![ansible-forum][ansible-forum-shield]

* **[Ansible.builtin.service_facts incorrect and simplified state](https://forum.ansible.com/t/ansible-builtin-service-facts-incorrect-and-simplified-state/39836)** ⭐ _new_ ⭐

## open issue: 🐛

* **[ansible.builtin.service_facts incorrect and simplified state #84607](https://github.com/ansible/ansible/issues/84607)** ⭐ _new_ ⭐

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
        - 'number_coffees'
  
    tasks:
  
    - name: Check sleep
      fail:
        msg: sorry it's not time yet
      when: number_coffees|int < 1
```
[reddit-shield]: https://img.shields.io/badge/reddit-white?style=flat-square&logo=reddit&logoColor=red
[ansible-forum-shield]: https://img.shields.io/badge/ansible%20forum-white?style=flat-square&logo=ansible&logoColor=black
<!--
**NomakCooper/nomakcooper** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

