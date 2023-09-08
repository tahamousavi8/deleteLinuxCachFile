## This bashscript clears pagecache, dentries, and inodes.
## Also it will free your swap area in linux server.

### use this instruction:

### 1- Install `curl` if you don't have it on your server:
```
sudo apt install curl
```
### 2- Run this bash:
```
curl https://raw.githubusercontent.com/tahamousavi8/deleteLinuxCachFile/main/deletecachfile.sh | bash
```

### 3- Reboot your server with this command:
```bash
sudo shutdown -r
```
