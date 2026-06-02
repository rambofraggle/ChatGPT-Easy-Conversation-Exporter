# ChatGPT-Easy-Conversation-Exporter
Export all your ChatGPT conversations at the click of a button — works with Enterprise, Team, and Business accounts where the built-in ChatGPT export feature is disabled. No installs. No command line. Nothing to type.

---

## Credits

Inspired by [ocombe's ChatGPT exporter gist](https://gist.github.com/ocombe/1d7604bd29a91ceb716304ef8b5aa4b5), which identified the relevant ChatGPT backend API endpoints.

---

## How it works

A one-time setup adds a button to your browser's bookmarks bar. After that, you go to chatgpt.com, click the button, and your conversations download automatically as a ZIP file.

---

## Quick start

1. Open `get-my-chatgpt-data.html` in your browser
2. Follow the on-screen instructions to drag the button to your bookmarks bar
3. Go to [chatgpt.com](https://chatgpt.com) and log in
4. Click your new **⬇️ Export My ChatGPT Data** bookmark
5. A progress overlay appears — when complete, a ZIP downloads to your Downloads folder

For detailed step-by-step instructions with screenshots, open the guide for your platform:

- 🪟 `Windows-Guide.html`
- 🍎 `Mac-Guide.html`

---

## What gets exported

- **JSON** — raw conversation data from the ChatGPT API
- **Markdown** — clean, readable text files, one per conversation
- Everything is bundled into a single **ZIP file**

---

## Browser compatibility

| Browser | Windows | macOS |
|---------|---------|-------|
| Chrome | ✅ | ✅ |
| Edge | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | — | ✅ |
| Brave | ✅ | ✅ |

---

## Notes

- You must be logged into chatgpt.com when you click the bookmark
- Sessions expire after a few hours — if you get a "not logged in" error, refresh chatgpt.com and try again
- Large conversation histories can take a few minutes to export — keep the tab open until the progress bar completes
