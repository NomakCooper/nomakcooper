## Hi there 👋

<div align="center">

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

</div>

<div align="center">

![HTML][html-shield]
![CSS][css-shield]
![JS][js-shield]
![Python][py-shield]
![YAML][yaml-shield]

</div>

[redhat-shield]: https://img.shields.io/badge/redhat-enterprice%20linux-red?style=for-the-badge&logo=redhat&logoColor=red
[oraclel-shield]: https://img.shields.io/badge/oracle-linux-red?style=for-the-badge&logo=oracle&logoColor=red
[oraclee-shield]: https://img.shields.io/badge/oracle-exadata-red?style=for-the-badge&logo=oracle&logoColor=red
[oracles-shield]: https://img.shields.io/badge/oracle-solaris-red?style=for-the-badge&logo=oracle&logoColor=red
[hpux-shield]: https://img.shields.io/badge/hp-ux-blue?style=for-the-badge&logo=hp&logoColor=blue
[hpsg-shield]: https://img.shields.io/badge/hp-serviceguard-blue?style=for-the-badge&logo=hp&logoColor=blue
[vcs-shield]: https://img.shields.io/badge/veritas-vcs-red?style=for-the-badge&logo=veritas&logoColor=red
[sfha-shield]: https://img.shields.io/badge/veritas-storage%20foundation-red?style=for-the-badge&logo=veritas&logoColor=red
[vsphere-shield]: https://img.shields.io/badge/vmware-vsphere-blue?style=for-the-badge&logo=vmware&logoColor=blue
[gengine-shield]: https://img.shields.io/badge/google%20cloud-compute%20engine-blue?style=for-the-badge&logo=googlecloud&logoColor=yellow
[ansible-shield]: https://img.shields.io/badge/ansible-automation-red?style=for-the-badge&logo=ansible&logoColor=white

[html-shield]: https://img.shields.io/badge/html-orange?style=for-the-badge&logo=html5&logoColor=white
[css-shield]: https://img.shields.io/badge/css-blue?style=for-the-badge&logo=css3&logoColor=white
[js-shield]: https://img.shields.io/badge/javascript-yellow?style=for-the-badge&logo=javascript&logoColor=white
[py-shield]: https://img.shields.io/badge/python-blue?style=for-the-badge&logo=python&logoColor=yellow
[yaml-shield]: https://img.shields.io/badge/yaml-red?style=for-the-badge&logo=yaml&logoColor=white

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

