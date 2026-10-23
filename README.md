# ha-provision apps

Home Assistant app repository for the fleet box agent. It holds the app metadata and nothing else.

Add this URL under Settings, Apps, App store, Repositories:

```
https://github.com/mihajlo-stojkovic/ha-provision-apps
```

The app runs the image `ghcr.io/mihajlo-stojkovic/ha-provision-box-agent:0.1.0` (linux/amd64 and linux/arm64). The image is a private GHCR package, because it contains the agent source. Supervisor needs a registry login for `ghcr.io` with read access to that package before it can install the app. `ha-provision` sets the login on the box.
