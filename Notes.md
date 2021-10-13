## Rancher

### Install

Ranker need https, simple installation below:

```
docker run -d --restart=unless-stopped \
  -p 9015:80 -p 443:443 \
  --privileged \
  rancher/rancher:latest
```
