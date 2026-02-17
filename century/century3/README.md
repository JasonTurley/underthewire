# Century3 -> Century4

https://underthewire.tech/wargames/century/3

> The password for Century4 is the number of files on the desktop.

---

To pass this level we need to count the number of files on the desktop. There are multiple ways
we can do this:

```
PS C:\users\century3\desktop> get-childitem | measure-object


Count    : 123
Average  :
Sum      :
Maximum  :
Minimum  :
Property :



PS C:\users\century3\desktop> (Get-ChildItem).Count
123
```

There's 123 files in the Desktop, so the credentials for the next level are:

| century4 | 123 |
