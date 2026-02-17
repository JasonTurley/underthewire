# Century2 -> Century3

https://underthewire.tech/wargames/century/2

> The password for Century3 is the name of the built-in cmdlet that performs the wget like function within PowerShell PLUS the name of the file on the desktop.
> 
> - If the name of the cmdlet is “get-web” and the file on the desktop is named “1234”, the password would be “get-web1234”.
> - The password will be lowercase no matter how it appears on the screen.

---

The cmdlet is `Invoke-WebRequest`. If you're unsure how to get this info, you can run `help wget` and is outputs the
help information for `Invoke-WebRequest`.

Doing a directory listing of the desktop, there is a single file named "443".

```
PS C:\users\century2\desktop> dir


    Directory: C:\users\century2\desktop


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/30/2018   3:29 AM            693 443
```

The credentials for the next level are:

| century3 | invoke-webrequest443 |
