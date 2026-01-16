# Medium Helper

A Chrome extension that automatically unlocks member-only articles on Medium.

## Features

- **Automatic detection**: Detects paywalled articles by looking for "become a member to read this story, and all of Medium"
- **Auto-unlock**: Automatically fetches and displays the full article content
- **Status indicator**: Shows a notification when an article is being unlocked or has been unlocked

## How to Install

1. Open `chrome://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked**
4. Select this folder

## How to Use

Just visit any paywalled Medium article. The extension will:

1. Automatically detect the paywall
2. Show "🔓 Unlocking article..." status
3. Fetch the full content
4. Replace the paywalled content
5. Show "✓ Article unlocked by Medium Helper" when done

No manual action required!

## Files

- `manifest.json` - Extension configuration
- `content.js` - Paywall detection and content injection
- `background.js` - Minimal service worker
- `logo.png` - Extension icon

## Privacy

This extension does not collect or send any personal data. It only fetches article content from freedium when a paywall is detected.
