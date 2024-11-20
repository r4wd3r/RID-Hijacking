# RID Hijacking: Maintaining Access on Windows Machines
[![Arsenal](https://github.com/toolswatch/badges/blob/master/arsenal/usa/2018.svg)](https://www.toolswatch.org/2018/05/black-hat-arsenal-usa-2018-the-w0w-lineup/)

The **RID Hijacking** hook, applicable to all Windows versions, allows setting desired privileges to an existent account in a stealthy manner by modifying some security attributes of an user.

By only using OS resources, it is possible to replace the RID of an user right before the primary access token is created, allowing to spoof the privileges of the hijacked RID owner.

## Modules
- [RID Hijacking with Metasploit](https://github.com/r4wd3r/RID-Hijacking/tree/master/modules/metasploit)
- [RID Hijacking with Powershell](https://github.com/r4wd3r/RID-Hijacking/tree/master/modules/powershell)
- [RID Hijacking with Empire](https://github.com/r4wd3r/RID-Hijacking/tree/master/modules/empire)
- [RID Hijacking with Crackmapexec](https://github.com/r4wd3r/RID-Hijacking/tree/master/modules/cme)
- [RID Hijacking with ibombshell](https://github.com/r4wd3r/RID-Hijacking/tree/master/modules/ibombshell)

## Paper
[ACM CCS Checkmate 24. Ghost in the SAM: Stealthy, Robust, and Privileged Persistence through Invisible Accounts](https://dl.acm.org/doi/10.1145/3689934.3690839)
```
@inproceedings{10.1145/3689934.3690839,
author = {Castro, Sebasti\'{a}n R. and C\'{a}rdenas, Alvaro A.},
title = {Ghost in the SAM: Stealthy, Robust, and Privileged Persistence through Invisible Accounts},
year = {2024},
isbn = {9798400712302},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3689934.3690839},
doi = {10.1145/3689934.3690839},
pages = {59–72},
numpages = {14}}
```

## Slides
[Derbycon 8.0](https://github.com/r4wd3r/RID-Hijacking/blob/master/slides/derbycon-8.0/RID_HIJACKING_DERBYCON_2018.pdf)

## References

[r4wsecurity: RID Hijacking - Maintaining access on Windows Machines](https://r4wsec.com/notes/rid_hijacking/)
