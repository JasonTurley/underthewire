# Century8 -> Century9

https://underthewire.tech/wargames/century/8

> The password for Century9 is the number of unique entries within the file on the desktop.

---

Each entry in the file is already unique, so simply counting the number of lines in the file will give the answer.

```
PS C:\users\century8\desktop> (get-content .\unique.txt).Count
696
```

Here's the commands to count unique entries in a file:
```
PS C:\users\century8\desktop> (get-content .\unique.txt | Sort-Object | Get-Unique).Count
696
```

So the credentials for the next level are:

| century9 | 696 |
