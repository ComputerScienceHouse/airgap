# airgap
Documentation for CSH's Airgap lab.

## Overview

#### Hardware
- [ ] What will we be working with here? 
- [ ] Remove or block RJ45 jacks in that room
- [ ] Locked or open rack? Depends on the level of trust and whether we want physical or virtual networking. If physical we should get NICs with >4 ports

#### Software
- [ ] Golden image on a container or proxmox level?
  - [ ]  Types of images
    - [ ]  Clean windows
    - [ ]  Clean linux
    - [ ]  Clean MacOS
    - [ ]  Kali images
    - [ ]  Other images with different types of tooling? What other workloads would be useful here?
- [ ] What applications do we want and how do we handle their management?
  - [ ]  Internal/local package repo, or should we try to pre-install a lot of stuff. I think the former might be less resource intensive on individual VMS
- [ ] Pre-made environments with many systems for CTF pentesting???

## Security Considerations

#### Vectors (ranked by priority high to low):
- [ ] Ethernet
- [ ] USB
- [ ] WiFi
- [ ] Bluetooth
- [ ] Other physical interfaces
- [ ] Extraneous RF Emissions

#### User Experience
- [ ] We can't do SSO or standard homedirs, this should probably just be one username and password
- [ ] What level of access and trust on proxmox do users get?
