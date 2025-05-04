# rndmzr
Chrome extension which *automagically* generates and submits Clockify timesheets based on a CAPEX/OPEX ratio profile.

## Motivation
Filling out timesheets is too much of a hassle - why bother? 😅

## Screenshots
![rndmzr](https://raw.githubusercontent.com/marchev/rndmzr/main/meta/app-screenshot.png)

## Tech/framework used
Built with:
- [Vue.js](https://vuejs.org/)
- [Buefy](https://buefy.org/)
- [Font Awesome](https://fontawesome.com/)
- [vue-web-extension](https://github.com/Kocal/vue-web-extension)

## Features
- Automagic randomized generation and submission of Clockify timesheets
- Historical timesheets browsing

## 📦 Download & Use the Pre-Built Extension
To skip the build process and just use the extension:

1. Visit the Releases page
2. Download the latest rndmzr-chrome-extension.zip
3. Unzip it
4. Open Chrome and go to chrome://extensions
5. Enable Developer Mode
6. Click Load unpacked
7. Select the unzipped folder
8. Fill in required settings configuration - Role & Clockify API key

## 🔧 Local Development Setup
This is a Vue 2-based Chrome extension. You can either run it locally for development or download a pre-built version from GitHub Releases for quick installation.

### Requirements

- WSL (Ubuntu) or Linux/macOS/Windows with Node.js
- Node.js (version 16 recommended)
- Yarn (installed via [Corepack](https://nodejs.org/api/corepack.html))
    - `corepack enable`
    - `corepack prepare yarn@stable --activate`

1. Clone the repo and navigate to the directory
2. `yarn serve`
3. In Chrome navigate to Extensions
4. Enable **Developer Mode**
5. Clock **Load unpacked** and point to the `rndmzr/dist` directory
6. Code and have fun 👻

## Project with a cause
This extension is **donationware** - all proceeds received would be donated to [SOS Children's Villages Bulgaria](https://sosbg.org/).

## License
[Commons Clause License Condition v1.0](https://commonsclause.com/)

The Software is provided to you by the Licensor under the License, as defined below, subject to the following condition.

Without limiting other conditions in the License, the grant of rights under the License will not include, and the License does not grant to you, the right to Sell the Software.

For purposes of the foregoing, “Sell” means practicing any or all of the rights granted to you under the License to provide to third parties, for a fee or other consideration (including without limitation fees for hosting or consulting/ support services related to the Software), a product or service whose value derives, entirely or substantially, from the functionality of the Software. Any license notice or attribution required by the License must also include this Commons Cause License Condition notice.
