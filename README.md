# CheatSheet
## Git
### Push existing folder to new repo
```
git init
git add .
git remote add origin \repo\
git branch -M main
git push -u origin main
```

### Sync existing repo to new computer
```
git clone \repo\
```

### Save credentials
```
git config --global credential.helper store
```

## Remote Servers
### SSH - Secure Shell
Open terminal to remote server:
```
SSH user@server.com
```

### SCP - Secure Copy
Copy file from remote server:
```
SCP user@server.com:/path/to/file.txt ~/path/to/destination
```
