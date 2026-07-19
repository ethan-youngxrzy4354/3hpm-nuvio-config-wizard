# 3HPM Nuvio Wizard v2026 - browser-based setup helper 2026

> **A browser-based setup helper for Nuvio v2026 that simplifies debrid integration, creates scraper manifest URLs, and produces Comet configuration in a modern web-first workflow.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ethan-youngxrzy4354/3hpm-nuvio-config-wizard?style=flat-square)](https://github.com/ethan-youngxrzy4354/3hpm-nuvio-config-wizard)

---

<p align="center">
  <a href="https://ethan-youngxrzy4354.github.io/3hpm-nuvio-config-wizard/">
    <img src="https://img.shields.io/badge/Download-3HPM%20Nuvio%20Wizard%20Latest-brightgreen?style=for-the-badge" alt="Download 3HPM Nuvio Wizard">
  </a>
</p>

> **[Direct Download - 3HPM Nuvio Wizard v2026](https://ethan-youngxrzy4354.github.io/3hpm-nuvio-config-wizard/)**

---

[Download Latest Build](https://ethan-youngxrzy4354.github.io/3hpm-nuvio-config-wizard/)

---

## About 3HPM Nuvio Wizard

3HPM Nuvio Wizard is a browser-based setup assistant created for the Nuvio v2026 workflow. Its role is to help prepare debrid-related setup pieces, generate scraper manifest URLs, and shape Comet configuration without needing a traditional desktop installation.

The project is delivered as a static web app, so you can open it directly in a browser and use it as a compact configuration companion. It is aimed at users who want a guided way to produce consistent setup output for the current release while keeping the whole process inside the web interface.

---

## Features

- Produces scraper manifest URLs for Nuvio-oriented setup flows
- Assembles Comet configuration output for the current release
- Includes support for a Connected Services workflow
- Encodes generated output in Base64 for transport or embedding
- Keeps API keys out of the generated manifest itself
- Operates as a static web app in the browser
- Works well as a lightweight tool for web-based configuration tasks
- Built around the Nuvio v2026 release path

---

## Installation

Clone or download the repository, then open the static web app in a browser.

```bash
git clone https://github.com/ethan-youngxrzy4354/3hpm-nuvio-config-wizard.git
cd REPO
```

After cloning, open the primary HTML file in your browser, or serve the folder through any local static server.

---

## Usage

1. Launch the app in a browser.
2. Provide the details required for your Nuvio setup flow.
3. Generate the scraper manifest URL or the Comet configuration.
4. Copy the Base64-encoded output when your workflow needs it.
5. Use the Connected Services flow if your setup depends on it.

Example local preview:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` and start the page from there.

---

## Configuration

Since this is a static web app, the main behavior is usually controlled by the page itself and by the values you enter during generation.

If you need to change defaults or labels, inspect the HTML and any included script file that powers the setup interface.

```text
Configuration location:
- Main HTML page
- Embedded script or linked JavaScript, if present
```

No API keys should be embedded in the generated manifest output.

---

## Requirements

- A modern web browser
- Access to the static app files
- Optional local static server for previewing or testing
- Enough storage for the repository files and generated text output
- A setup path compatible with the Nuvio v2026 workflow

---

## FAQ

**Do I need to install anything?**  
No separate installer is required. The project is meant to run as a browser-based static web app.

**Where do updates come from?**  
Updates are provided through the repository and its published build or hosted page.

**Can the generated configuration be changed?**  
Yes. You can modify the inputs in the app and review the generated manifest or Comet configuration before using it.

**What should I do if the page will not load locally?**  
Make sure you are opening the correct HTML file or serving the folder with a local web server.

**Are API keys stored in the manifest?**  
The generated manifest is designed so that API keys are not embedded directly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
