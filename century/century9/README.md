# Century9 -> Century10

https://underthewire.tech/wargames/century/9

> The password for Century10 is the 161st word within the file on the desktop.
>
> **IMPORTANT NOTE**
> - The password will be lowercase no matter how it appears on the screen.

---

The file contains a bunch of words separated by spaces. We can use the `-Delimiter` option to split
the words.

```
PS C:\users\century9\desktop> (get-content -Delimiter " " .\Word_File.txt) | Select-Object -Index 160
pierid

PS C:\users\century9\desktop> (get-content -Delimiter " " .\Word_File.txt)[160]
pierid
```

The creds for the next level:

| century10 | pierid|
