### Change Hostname
1. Introduce the next line in terminal:

```
hostnamectl set-hostname server.example.com
```
2. Restart the hostnamectl service:
```
systemctl restart systemd-hostnamed
```