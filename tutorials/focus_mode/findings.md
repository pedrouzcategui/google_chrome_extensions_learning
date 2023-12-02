# Extension Service Worker

Extensions is a feature that allows to monitor browser events in the background.
Service workers are special JavaScript environments that are loaded to handle events and terminated when they are no longer needed.

# How do you register a service worker?

You include it in the manifest.json

```json
{
  "manifest_version": 3,
  "name": "Focus Mode",
  "description": "Enable focus mode on Chrome's official Extensions and Chrome Web Store documentation.",
  "version": "1.0",
  "icons": {
    "16": "images/icon-16.png",
    "32": "images/icon-32.png",
    "48": "images/icon-48.png",
    "128": "images/icon-128.png"
  },
  "background": {
    "service_worker": "background.js"
  },
  "action": {
    "default_icon": {
      "16": "images/icon-16.png",
      "32": "images/icon-32.png",
      "48": "images/icon-48.png",
      "128": "images/icon-128.png"
    }
  }
}
```

Search the following:

- StorageAPI
- IndexedDB
- Action Badges
- ActiveTab Permission
- Permissions
- Commands key in manifest.json
