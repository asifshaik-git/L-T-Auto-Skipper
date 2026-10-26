# ⚡ Auto Skipper

A Chrome extension experiment designed to automate video playback and SCORM learning-module completion workflows.

## Features

- Chrome Extension Manifest V3
- Automatic video playback speed adjustment
- SCORM API interaction
- Progress and completion-status handling

## Project Structure

```text
auto-skipper/
├── manifest.json
├── content.js
└── README.md
```

## Installation for Testing

1. Download or clone this repository.
2. Open `chrome://extensions/` in Google Chrome.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the project folder containing `manifest.json`.

## Permissions and Responsible Use

This extension interacts with video elements and SCORM completion APIs on matching pages. Its current configuration uses broad page matching. Review its permissions and behavior before installing it.

Use only on systems and training modules where you have authorization. Do not use it to misrepresent completion of mandatory training or assessments.

## Technology

- JavaScript
- Chrome Extensions API
- SCORM API

## Version

1.0
