![docker-publish-to-dh](https://github.com/swaglive/docker-gcsfuse/workflows/docker-publish-to-dh/badge.svg)

# Usage

```Dockerfile
FROM gcsfuse as gcsfuse

FROM alpine

COPY --from gcsfuse /usr/local/bin/gcsfuse /usr/local/bin/gcsfuse
```
