# Century0 -> Century1

https://underthewire.tech/wargames/century/0

> The goal of this level is to log into the game. Do the following in order to achieve this goal.
> 
> 1. Obtain the initial credentials via the #StartHere channel on our Slack (https://underthewire.herokuapp.com/).
> 
> 2. After obtaining the credentials, connect to the server via SSH. You will need a SSH client such as Putty. The host that you will be connecting to is century.underthewire.tech, on port 22.
> 
> 3. When prompted, use the credentials for the applicable game found in the #StartHere Slack channel.
> 
> 4. You have successfully connected to the game server when your path changes to "PS C:\Users\Century1\documents>".

---

The Slack channel doesn't appear to be online in the big 2026. However, finding the password online was pretty easy. We can login with the credentials `century1:century1` via SSH.

```
# Password is century1
ssh century1@century.underthewire.tech
```

