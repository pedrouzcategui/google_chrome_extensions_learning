# What is Manifest.json

Manifest.json is the configuration file of the project, and it contains important information about the project, like the project name, the necessary permissions, the content script, etc.
Manifest.json must be located in the root of the project.

Manifest Keys: https://developer.chrome.com/docs/extensions/mv3/manifest/
Manifest Examples: https://developer.chrome.com/docs/extensions/mv3/manifest/#manifest-examples

# What is a service worker

Service worker is a JS based-event script that runs on the background, that cannot access the DOM, but can interact with other APIs, usually used to listen to new actions.

# What is a content script

The main .js content script is what provides functionality to the actual extension, is where all of the js code of the extension lives.

# What is an HTML extension page

An HTML extension page is basically the UI that you design for the actual extension, it also has multiple things to learn:

- Popup
- Options
- Side Panels

More:

- UI Elements: https://developer.chrome.com/docs/extensions/mv3/user_interface/
- Extension Security Best Practices: https://developer.chrome.com/docs/extensions/mv3/security/
- List of Chrome Extension Capabilities: https://developer.chrome.com/docs/extensions/mv3/devguide/
- Quality Guidelines: https://developer.chrome.com/docs/webstore/program-policies/quality-guidelines-faq/

Reference:

- https://developer.chrome.com/docs/extensions/mv3/architecture-overview/
