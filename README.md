# CanvasFlow v2 - graphic design app 2026

> **CanvasFlow is a client-side web PWA for creating graphic designs with shapes, text, images, templates, and PNG export, available in version 2.**

[![Platform](https://img.shields.io/badge/Platform-web%20PWA-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/caleb-davislftj6913/canvasflow-design-app-v2?style=flat-square)](https://github.com/caleb-davislftj6913/canvasflow-design-app-v2)

---

<p align="center">
  <a href="https://caleb-davislftj6913.github.io/canvasflow-design-app-v2/">
    <img src="https://img.shields.io/badge/Download-CanvasFlow%20Latest-brightgreen?style=for-the-badge" alt="Download CanvasFlow">
  </a>
</p>

> **[Download CanvasFlow v2](https://caleb-davislftj6913.github.io/canvasflow-design-app-v2/)**

---

[Download Latest Build](https://caleb-davislftj6913.github.io/canvasflow-design-app-v2/)

---

## What is CanvasFlow?

CanvasFlow provides a browser-based canvas for graphic design tasks. Combine shapes, text, and images on a visual workspace, or use one of the included starter templates as the foundation for a new design.

As a progressive web app, CanvasFlow performs its work on the client and can cache application resources for offline use. Designs are saved as PNG files when exported, and project information remains on the local device rather than depending on a server-side editing system.

---

## Included capabilities

- Create compositions by placing shapes, text, and images with drag-and-drop controls
- Start from a set of ready-made design templates
- Save completed canvas designs as PNG images
- Continue using cached application resources when connectivity is unavailable
- Keep project data in local device storage
- Use CanvasFlow entirely through a client-side web application
- Evaluate the app with a 7-day free trial
- Unlock the application once, including the available option to remove watermarks

---

## Getting started

### Open the hosted PWA

Launch the current build in a supported browser:

[Launch CanvasFlow](https://caleb-davislftj6913.github.io/canvasflow-design-app-v2/)

When supported by the browser, choose its install command to add the PWA. Once the app has been opened initially, offline availability is based on the resources cached by the browser.

### Serve a local copy

Clone the repository and enter its directory:

```bash
git clone https://github.com/caleb-davislftj6913/canvasflow-design-app-v2.git
cd REPO
```

Use any static web server to serve the project files. This Python command is one option:

```bash
python3 -m http.server 8080
```

Then browse to `http://localhost:8080/` to open CanvasFlow.

---

## Basic workflow

1. Open CanvasFlow in a compatible browser.
2. Choose either an empty canvas or a starter template.
3. Add shapes, text, and images to the workspace by dragging them into place.
4. Adjust the arrangement with the canvas editor.
5. Use the export function to create a PNG file.
6. Return to the app on the same device to use project data saved locally.

For offline use, visit the hosted application once with an internet connection. This gives the PWA an opportunity to cache the resources it needs.

---

## Storage and configuration

The normal browser-based setup does not need a separate server configuration file. The browser handles application-resource caching, and project data is maintained in local device storage.

Browser site settings generally provide controls for inspecting or deleting stored data. Removing the site's stored data can also delete CanvasFlow projects saved locally.

---

## System requirements

- A current web browser that supports PWAs and local storage
- JavaScript turned on
- Internet connectivity for the first hosted launch and for application updates
- Available browser storage for locally saved projects
- Enough local disk space for cached application resources and exported PNG files

For development or offline testing, CanvasFlow may also be delivered through a local static web server.

---

## Common questions

### How do I open CanvasFlow?

Open the [latest hosted build](https://caleb-davislftj6913.github.io/canvasflow-design-app-v2/) to access the web PWA.

### Does the app support offline use?

CanvasFlow provides offline caching. First load the app while connected; afterward, offline operation depends on the browser and the resources it has retained.

### Where does CanvasFlow save projects?

Projects are kept in browser storage on the current device. CanvasFlow is not presented as a synchronized workspace backed by a server.

### How can I create an image from a design?

Finish arranging the canvas, then select the application's PNG export control to save the result as an image.

### Is a free trial available?

Yes. CanvasFlow offers a 7-day free trial. It also has a one-time unlock, and watermark removal is included in the listed unlock features.

### What can I check if CanvasFlow will not open?

Make sure JavaScript is active, refresh the page, and verify that the browser has enough available storage. When working offline, reconnect and open the hosted build again to allow cached resources to refresh.

### How are application updates delivered?

Open the hosted build with an internet connection. The PWA can obtain newer application resources through its ordinary cache refresh process.

---

## Future work

- Further improve the canvas editing experience
- Make templates easier to organize and find
- Continue strengthening offline usability
- Refine the PNG export process

---

## License

CanvasFlow is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for details.
