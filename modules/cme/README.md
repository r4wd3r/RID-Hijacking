## Overview

The **RID Hijacking** hook, applicable to all Windows versions, allows setting desired privileges to an existent account in a stealthy manner by modifying some security attributes of an user.

By only using OS resources, it is possible to replace the RID of an user right before the access token is created. Taking advantage of some Windows Local Users Management integrity issues, this module will allow to authenticate with one known account credentials (like GUEST account), and access with the privileges of another existing account (like ADMINISTRATOR account), even if the spoofed account is disabled.

## Module Testing
The module `Invoke-RIDHijacking` is compatible with Powershell >=2.0. It requires administrative privileges to be executed. 

This module has been tested against:

- Windows XP, 2003. (32 bits)
- Windows 8.1 Pro. (64 bits)
- Windows 10. (64 bits)
- Windows Server 2012. (64 bits)

## Module options

![cme_module_options](https://user-images.githubusercontent.com/14118912/53310153-985de780-3879-11e9-9d64-444bec528231.PNG)

## Execution

1. Authenticate with the _unprivileged_ local user account. Login success but without privileges.
2. Set the _Administrator built-in_ account default **RID (500)** to the _unprivileged_ local user account
3. Authenticate again with _unprivileged_ local user account. Now it has _Administrator_ privileges.

![cme_demo](https://user-images.githubusercontent.com/14118912/53310164-a6ac0380-3879-11e9-91e5-9e198e998d21.PNG)

## References
https://github.com/r4wd3r/RID-Hijacking

https://csl.com.co/rid-hijacking/

https://r4wsecurity.blogspot.com/2017/12/rid-hijacking-maintaining-access-on.html
