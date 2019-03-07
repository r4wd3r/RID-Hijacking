# RID Hijacking: Maintaining Access on Windows Machines
[![Arsenal](https://github.com/toolswatch/badges/blob/master/arsenal/usa/2018.svg)](https://www.toolswatch.org/2018/05/black-hat-arsenal-usa-2018-the-w0w-lineup/)

The **RID Hijacking** hook, applicable to all Windows versions, allows setting desired privileges to an existent account in a stealthy manner by modifying some security attributes of an user.

By only using OS resources, it is possible to replace the RID of an user right before the access token is created. To automatize the attack, a Metasploit module was developed. It requires a *meterpreter* session against the victim.

## Metasploit Module

[post/windows/manage/rid_hijack](https://github.com/rapid7/metasploit-framework/blob/master/modules/post/windows/manage/rid_hijack.rb)

![rid_hijack](https://github.com/r4wd3r/RID-Hijacking/blob/master/rid_hijack.png)

## Powershell: Invoke-RIDHijacking

![rid_hijack](https://github.com/r4wd3r/RID-Hijacking/blob/master/modules/powershell/rid_hijack_posh.png)

## Empire

![rid_hijack](https://github.com/r4wd3r/RID-Hijacking/blob/master/modules/empire/rid_hijack_empire.png)

## CrackMapExec

![rid_hijack](https://github.com/r4wd3r/RID-Hijacking/blob/master/modules/cme/rid_hijack_cme.PNG)

## ibombshell

![rid_hijack](https://github.com/r4wd3r/RID-Hijacking/blob/master/modules/ibombshell/rid_hijack_ibombshell.png)

## References

[CSL LABS: RID Hijacking on Windows](http://csl.com.co/rid-hijacking/)

[r4wsecurity: RID Hijacking - Maintaining access on Windows Machines](https://r4wsecurity.blogspot.com/2017/12/rid-hijacking-maintaining-access-on.html)
