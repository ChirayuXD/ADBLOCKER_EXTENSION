# Simple Ad Blocker

## Overview

Simple Ad Blocker is a Chrome extension designed to block specific ad URLs, providing a cleaner and more enjoyable browsing experience. This extension uses the declarativeNetRequest API to block network requests to known advertising domains.

## Features

- Blocks ads from `doubleclick.net`
- Blocks ads from `googleadservices.com`

## Installation

1. **Download the repository**:
   - Clone the repository or download the ZIP file and extract it to a directory on your computer.

2. **Load the extension in Chrome**:
   - Open Chrome and navigate to `chrome://extensions/`.
   - Enable "Developer mode" by toggling the switch in the top right corner.
   - Click on the "Load unpacked" button.
   - Select the directory where you extracted the repository.

## Files

- `manifest.json`: This is the configuration file for the Chrome extension, containing metadata and permissions required by the extension.
- `rules.json`: This file contains the ruleset that specifies which URLs should be blocked.

## Usage

Once installed, the Simple Ad Blocker will automatically start blocking network requests to the specified ad domains. No further configuration is needed.

## Contributing

If you want to contribute to the project, feel free to fork the repository and submit pull requests. Your contributions are welcome!

---

Thank you for using Simple Ad Blocker! Enjoy a cleaner browsing experience.