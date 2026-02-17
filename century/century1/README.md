# Century1 -> Century2

https://underthewire.tech/wargames/century/1

> The password for Century2 is the build version of the instance of PowerShell installed on this system.
> 
> **IMPORTANT NOTE**
> 
> - The format is as follows: **.*.*****.****
> - Include all periods
> - Be sure to look for build version and NOT PowerShell versionIMPORTANT:Once you feel you have completed the Century1 challenge, start a new connection to the server, and log in with the username of Century2 and this password will be the answer from Century1. If successful, close out the Century1 connection and begin to solve the Century2 challenge. This concept is repeated over and over until you reach the end of the game.

---

Once logged in, run the command `$PSVersionTable` to get the build version:

```powershell
PS C:\users\century1\desktop> $PSVersionTable

Name                           Value
----                           -----
PSVersion                      5.1.14393.8688
PSEdition                      Desktop
PSCompatibleVersions           {1.0, 2.0, 3.0, 4.0...}
BuildVersion                   10.0.14393.8688
CLRVersion                     4.0.30319.42000
WSManStackVersion              3.0
PSRemotingProtocolVersion      2.3
SerializationVersion           1.1.0.1
```

You can get just the BuildVersion with:

```powershell
($PSVersionTable.BuildVersion).ToString()
10.0.14393.8688
```

The credentials for the next level

| century2 | 10.0.14393.8688 |
