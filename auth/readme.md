# Auth folder

This is where the `keyfile` goes in for the replica set 🔑

To create one do the following:

```
openssl rand -base64 700 > file.key
chmod 400 file.key
sudo chown 999:999 file.key
```
