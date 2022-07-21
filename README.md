OTA Updates
======================

### About

Source for a docker container for a node-red based OTA update notification and download service.

repo is synced with docker hub at brianapley/ota_updates.



## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name eventapi brianapley/ota_updates.
```

Once launched, UI can be accessed via http://host:1880/.

