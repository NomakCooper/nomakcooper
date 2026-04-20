## Hi there 👋

![user](https://img.shields.io/badge/NomakCooper-blue?logo=github&logoColor=white&label=Profile)

```
╭─── Profile v1.0 ──────────────────────────────────────────────────────────────────────────╮
│                                                    │ Tips for getting started             │
│                 Welcome back Marco!                │ Run /profile!                        │
│                                                    │ ─────────────────────────────────────│
│       NomakCooper's Organization                   │                                      │
│       /nomakcooper                                 │                                      │
╰───────────────────────────────────────────────────────────────────────────────────────────╯
  ⎿  SessionStart:startup says: [nomakcooper] recent context
     ────────────────────────────────────────────────────────────
                                          
██████╗ ██████╗  ██████╗ ███████╗██╗██╗     ███████╗
██╔══██╗██╔══██╗██╔═══██╗██╔════╝██║██║     ██╔════╝
██████╔╝██████╔╝██║   ██║█████╗  ██║██║     █████╗  
██╔═══╝ ██╔══██╗██║   ██║██╔══╝  ██║██║     ██╔══╝  
██║     ██║  ██║╚██████╔╝██║     ██║███████╗███████╗
╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝╚══════╝

❯ /profile 
  ⎿  Load profile

  ╭──────────────────────────────────────────────────────────────────────────────────────╮
  │                                                                                      │
  │ Profile                                                                              │
  │                                                                                      │
  │ Name                              Marco                                              │
  │ Alias                             Nocchia                                            │
  │ Username                          NomakCooper                                        │
  │ Country                           Italy                                              │
  │                                                                                      │
  │ Role                              Diagiostic Operator                                │
  │                                                                                      │
  ╰──────────────────────────────────────────────────────────────────────────────────────╯

──────────────────────────────────────────────────────────────────────────────────────────
❯  /profile
──────────────────────────────────────────────────────────────────────────────────────────
  Model: Profile 1.0 | Ctx: 0 | ⎇ main | (+0,-0)                                   
  Context: [░░░░░░░░░░░░░░░░] 0k/200k (0%) | Mem: 7.8G/16.0G
  v1.0 | Thinking: medium | Cost: $0.00 | Session: 0.0%
                                              
```

#### is it time? :thinking:

```yaml
---
  - name: Life Module
    hosts: localhost
    become: true
    become_method: sudo
  
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
<!--
**NomakCooper/nomakcooper** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

