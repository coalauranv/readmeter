# readmeter

MV3 extension playground: page reading-time estimator

Started as a weekend hack, grew on me.

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- Popup shows today's total focus time
- No remote calls, everything stays local
- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
