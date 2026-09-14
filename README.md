# Firefox Simple One Line

A simple one-line Firefox CSS theme, targeting Nova UI.

![screenshot](./assets/screenshot.png)

## Installation

### Option A: Using [Firefox-CSS-Theme](https://github.com/easonwong-de/Firefox-CSS-Theme)

Clone the repo and install dependencies:

```bash
git clone https://github.com/easonwong-de/Firefox-Simple-One-Line.git
cd Firefox-Simple-One-Line
npm install
```

Then run:

```bash
npm run install:theme
```

### Option B: Manual Installation

1. Open Firefox and navigate to `about:config` via the address bar.
2. Accept the warning prompt and search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
3. Toggle the preference to `true`.
4. Navigate to `about:support` in Firefox.
5. Locate the **Profile Directory** (or **Profile Folder** / **Show in Finder**) row and click **Open Directory** / **Open Folder**.
6. Inside the profile folder, create a directory named `chrome` if it does not already exist.
7. Copy `userChrome.css` and the `theme` directory into the `chrome` directory.
8. Restart Firefox.

## Development

This theme was built entirely using the [Firefox-CSS-Theme MCP](https://github.com/easonwong-de/Firefox-CSS-Theme#mcp-server-usage).
