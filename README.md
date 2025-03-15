# My City Doors Opera Browser Extension

The **My City Doors** Opera browser extension gives users direct access to browse and shop premium European-style doors from My City Doors, right within the Opera browser.

---

## Features

- Quick access to premium door collections.
- Real-time notifications for special offers.
- Easy navigation and seamless browsing.
- Optimized experience for homeowners, contractors, and interior designers.

---

## Environment Setup

**OS Version:**  
- Windows 10/11, macOS Monterey (12+) or later, Ubuntu 20.04+

**Required Tools:**  
- Node.js v18.x LTS  
- npm v9.x  
- zip utility  

---

## Step-by-Step Build Instructions

```sh
# Clone repository
git clone https://github.com/mycitydoors/opera-browser-extension.git
cd opera-browser-extension

# Install dependencies
npm install

# Build extension
npm run build

# Package extension
zip -r opera-extension.zip dist/*
