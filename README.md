# ha-provision apps

Home Assistant app repository for the fleet box agent. It holds the app metadata and nothing else.

Add this URL under Settings, Apps, App store, Repositories:

```
https://github.com/mihajlo-stojkovic/ha-provision-apps
```

The app runs the image `ghcr.io/mihajlo-stojkovic/ha-provision-box-agent:0.4.0` (linux/amd64 and linux/arm64). The image is a public GHCR package, so Supervisor pulls it without a registry login.
