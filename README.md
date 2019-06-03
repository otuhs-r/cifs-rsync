# cifs-rsync

```dockerfile
FROM alpine
RUN apk add --update samba-client samba-common cifs-utils rsync -y \
    && rm -rf /var/cache/apk/*
```
