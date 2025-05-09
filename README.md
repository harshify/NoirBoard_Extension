# NoirBoard Chrome/Firefox Extension

NoirBoard is a sleek, dark-themed productivity extension designed to enhance your workflow with elegance and simplicity.

## 📸 Screenshots

### 🧠 Main Dashboard

![NoirBoard Main](./Images/noirboard_main.png)

### 💸 Expense Tracker

![Expense Tracker](./Images/noirboard_2.png)

---

## 🔧 Installation Guide

### ⚙️ For Chrome

1. Open **Chrome** and go to `chrome://extensions/`.
2. Enable **Developer mode** (top-right toggle).
3. Click **"Load unpacked"**.
4. Select the `dist` folder from this repository.
5. NoirBoard will now appear in your extensions list.

### 🦊 For Firefox

1. Open **Firefox** and go to `about:debugging#/runtime/this-firefox`.
2. Click **“Load Temporary Add-on…”**.
3. Select any file from the `dist` folder (e.g., `manifest.json`).
4. The extension will be temporarily loaded for your session.

---

## 🚀 Using the Extension

Once installed:

- Click the **NoirBoard icon** in the toolbar to activate the dashboard.
- All actions and settings are auto-saved using Chrome's `storage.sync` API, allowing seamless syncing across your devices.

> Note: For sync to work, ensure you're logged into Chrome with sync enabled.

---

## 📁 Project Structure

```
NoirBoard/
├── dist/
│   ├── manifest.json
│   ├── background.js
│   ├── popup.html
│   ├── popup.js
│   ├── style.css
│   └── ... other extension files
├── noirboard_main.png
├── noirboard_2.png
└── README.md
```

---

## 🧠 Tech Stack

- Vanilla JS / HTML / CSS
- Chrome Extensions API
- `chrome.storage.sync` for persistent, cross-device settings

---

## 📌 Notes

- The extension is already built and ready — no need to run any build commands or install dependencies.
- If you make edits, reloading the extension in `chrome://extensions` will apply the changes.

---

## 📬 Contribute

Feel free to fork the project or submit issues for bugs, suggestions, or improvements.

---

```
Happy Productivity with NoirBoard!
```
