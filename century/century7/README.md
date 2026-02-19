# Century7 -> Century8

https://underthewire.tech/wargames/century/7

> The password for Century8 is in a readme file somewhere within the contacts, desktop, documents, downloads, favorites, music, or videos folder in the user’s profile.
> 
> **IMPORTANT NOTE**
> - The password will be lowercase no matter how it appears on the screen.

---

Read the help of `Get-ChildItem` and use the -Recurse and -File flags to find the readme file:

```
PS C:\users\century7\Desktop> Get-ChildItem "C:\users\century7\Readme*" -Recurse -File


    Directory: C:\users\century7\Downloads


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/30/2018   3:29 AM              7 Readme.txt


PS C:\users\century7\Desktop> type C:\users\century7\Downloads\Readme.txt
7points

```

So the credentials for the next level are:

| century8 | 7points |
