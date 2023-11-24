# Additional loopback addresses (in MacOS)

This script help to create additional loopback addresses in MacOS. Localhost (127.0.0.1) is always left alone.

To enable all 127.x.x.x addresses in `/etc/hosts` for loopback:
```
sudo ./loopback enable
```

To clear all loopback addresses (except 127.0.0.1):
```
sudo ./loopback disable

```
To enable all 127.x.x.x addresses in `/etc/hosts` for loopback and clear all other loopback addresses (except 127.0.0.1):
```
sudo ./loopback trim
```

To show current loopback addresses (other than 127.0.0.1):
```
./loopback ips
```

To show current 127.x.x.x addresses from `/etc/hosts` (other than 127.0.0.1):
```
./loopback hosts
```

