Update-Management
======================

### About

This is a project that utilizes a pub/sub data broker within an OTA use case for updating IoT devices with firmware and software updates.

The features and benefits of this project include-

-Instant notifications to IoT devices that new updates are available. No longer will devices have to wait for a polling interval to determine if an update is available. Providing push notifications mean faster update campaigns, more secure devices (as critical security patches can be instantly pushed, as opposed to waiting when a device asks via polling), and better efficient via avoiding needless polling when no update is available.

-Campaign scheduling control- devices can be selectively updated, either on an individual basis (for re-flashing in addressing specific customer issues), population segments for Blue/Green rollouts or other cohort-based updating, or global updates to all devices.

-Real-time client telemetry, delivered via the same pub/sub channel, that provide instant observability into the update campaign. 


## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name eventapi brianapley/update-management.
```

Once launched, UI can be accessed via http://host:1880/.

