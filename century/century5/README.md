# Century5 -> Century6

https://underthewire.tech/wargames/century/5

> The password for Century6 is the short name of the domain in which this system resides in PLUS the name of the file on the desktop.
>
> **IMPORTANT NOTE**
> 
> - If the short name of the domain is “blob” and the file on the desktop is named “1234”, the password would be “blob1234”.
> - The password will be lowercase no matter how it appears on the screen.

---

Get the short name of the domain

```
PS C:\users\century5\desktop> (Get-WmiObject Win32_NTDomain).DomainName
underthewire
```
The file in the directory:

```
PS C:\users\century5\desktop> dir


    Directory: C:\users\century5\desktop


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/30/2018   3:29 AM             54 3347
```

The creds for the next level are

| century6 | underthewire3347 |
