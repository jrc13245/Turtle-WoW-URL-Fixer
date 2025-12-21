# 🐢 Turtle-WoW URL Fixer

A Chrome/Edge extension that automatically redirects all old Turtle WoW URLs to the new turtlecraft.gg domain.

## Why?

Turtle WoW has moved to a new domain. Many community links on Discord, forums, guides, and other websites still point to the old `turtle-wow.org` URLs, which no longer work. This extension automatically redirects them so you don't have to manually fix every link.

## Redirects

| Old URL | New URL |
|---------|---------|
| `turtle-wow.org/*` | `turtlecraft.gg/*` |
| `forum.turtle-wow.org/*` | `forum.turtlecraft.gg/*` |
| `database.turtle-wow.org/*` | `database.turtlecraft.gg/*` |
| `talents.turtle-wow.org/*` | `talents.turtlecraft.gg/*` |

All paths and query parameters are preserved.

## Installation

1. Download the [latest release](../../releases/latest) (ZIP file)
2. Extract the ZIP to a folder
3. Open Chrome/Edge and go to `chrome://extensions` (or `edge://extensions`)
4. Enable **Developer mode** (toggle in the top right)
5. Click **Load unpacked**
6. Select the extracted folder

That's it! Old Turtle WoW links will now automatically redirect.

## How it works

This extension uses Chrome's `declarativeNetRequest` API to intercept requests at the network level — before DNS resolution even happens. This means it works even though the old domain no longer exists.

## Compatibility

- ✅ Google Chrome
- ✅ Microsoft Edge
- ✅ Brave
- ✅ Other Chromium-based browsers

## License

MIT — Feel free to use, modify, and share.

---

*For the Turtle WoW community* 🐢
