
# CTF-Write-Ups

A repository of retired CTF challenge write-ups, organised by platform and challenge/machine name. Screenshots and other files are in subfolders with relative links. All tools and techniques demonstrated are for educational purposes only.

## File Structure

```
# example URLs
tryhackme[.]com/r/room/basicpentestingjt
app[.]hackthebox[.]com/machines/Blue

# example folder structures
THM-basicpentestingjt/writeup.md
THM-basicpentestingjt/img/
THM-basicpentestingjt/file/

HTB-Blue/writeup.md
HTB-Blue/img/
HTB-Blue/file/
```

Relative links adapt to the current file location within the repository, for example:

```
# linking to a file
[setup-guide.pdf](file/setup-guide.pdf)

# linking an image
![Alt text](img/Web_LoginScreen.png)

```

## Example Template

```
# PlatformName | ChallengeName

**Disclaimer:** The tools and techniques demonstrated in this challenge are for educational purposes only. They should never be performed on any system without the explicit written consent of the owner. The vulnerable software shown may not represent the latest version available and may have been intentionally altered to be vulnerable. The steps described may not be safe to run, and users proceed at their own risk.

# Reconnaissance

Host discovery, port scanning, initial service enumeration.


# Initial Access

Obtaining a foothold on the host and capturing the user flag.


# Post-Exploitation

Privilege escalation and capturing the root flag.


# Mitigations

Discuss how the vulnerabilities found could be fixed.

```
