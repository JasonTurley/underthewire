# Century4 -> Century5

https://underthewire.tech/wargames/century/4

> The password for Century5 is the name of the file within a directory on the desktop that has spaces in its name.

---

Doing a dir listing of the desktop we see one file with spaces.

```
PS C:\users\century4\desktop> dir


    Directory: C:\users\century4\desktop


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        4/27/2025   7:57 PM                Can You Open Me

```

We can dir the file by adding quotes around it or by pressing TAB to tab-complete it automatically.

```
PS C:\users\century4\desktop> dir '.\Can You Open Me'


    Directory: C:\users\century4\desktop\Can You Open Me


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        4/27/2025   7:57 PM             24 15768
```

For fun, I printed the contents of the file.

```
PS C:\users\century4\desktop> Get-Content '.\Can You Open Me\15768'
Great Work!  Keep it up.
```

The creds for the next level are

| century5 | 15768 |
