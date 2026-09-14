# Firefox Simple One Line

A simplistic one-liner Firefox CSS theme, targetting Nova UI.

## Installation

### Using firefox-css-theme

Clone and install dependencies:

```bash
git clone https://github.com/easonwong-de/Firefox-Simple-One-Line.git
cd Firefox-Simple-One-Line
npm install
```

Then run:

```bash
npm run install:theme
```

### Manual Installation

1. Open Firefox and navigate to `about:config` via the address bar.
2. Accept the warning prompt and search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
3. Toggle the preference to `true`.
4. Navigate to `about:support` in Firefox.
5. Locate the **Profile Directory** (or **Profile Folder** / **Show in Finder**) row and click **Open Directory** / **Open Folder**.
6. Inside the profile folder, create a directory named `chrome` if it does not already exist.
7. Copy `userChrome.css` and the `theme` directory into the `chrome` directory.
8. Restart Firefox.
