# Mini App Frontend

This is a free front-end sample for Telegram WebApp usage.

To launch it on HTTPS, deploy the folder behind any free static host with HTTPS enabled or serve it via a local proxy.

The app sends a JSON payload like:

{
  "action": "miniapp_submit",
  "blur": { "x": 0.38, "y": 0.42, "w": 0.26, "h": 0.18 },
  "subtitle": { "x": 0.5, "y": 0.85 }
}
