# homelab-reloader

This is a mirco-services repo for deploying
[reloader](https://github.com/stakater/Reloader)
into [my homelab](https://github.com/charlesthomas/homelab).

## the annotation:

```yaml
kind: Deployment
metadata:
  annotations:
    reloader.stakater.com/auto: "true"
```

---
This repo is templated via
[homelab-template](https://github.com/charlesthomas/homelab-template)
and automatically updated via
[🤖 Templatron](https://github.com/charlesthomas/templatron).
