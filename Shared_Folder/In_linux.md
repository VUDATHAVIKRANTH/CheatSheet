## Creating Shared Floder in linux

1. create a user group whom we want to share.
```
sudo groupadd <groupname>
```
add users to the group

```
sudo usermod -aG <groupname> user1
```
2. change group owership of folder
```
sudo chgrp <groupname> <path of shared folder>
```

3. enable group write permission

```
sudo chmod 2775 <path of shared folder>
```
