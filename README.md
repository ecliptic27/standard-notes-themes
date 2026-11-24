# Everforest and Tokyo Night for Standard Notes

## Hosting with GitHub Pages
1. Create a public repository named `sn-themes` in your GitHub account (use a pseudonym if desired).
2. Extract this archive. In both ext.json files replace every `__BASE_URL__` with `https://YOUR-USERNAME.github.io/sn-themes` (no trailing slash).
3. Upload the contents of the extracted folder to the repository root, preserving both theme directories. Commit.
4. In Settings > Pages, choose Deploy from a branch, main, / (root), then Save.
5. When Pages is live, open each manifest URL in a browser and confirm it shows JSON, then enter it in Standard Notes > Preferences > Plugins > Install Custom Plugin.
6. Activate the theme. If it fails, check that the CSS and ZIP URLs are reachable and that the app permits custom plugins.

Manifest paths: `/everforest/ext.json` and `/tokyo-night/ext.json`.

The themes contain CSS only, no JavaScript. Desktop ZIP files contain package.json and theme.css at their root. These are initial ports, not tested inside Standard Notes. Individual editors may use their own styling.

Palette inspiration: https://github.com/sainnhe/everforest and https://github.com/enkia/tokyo-night-vscode-theme.
Standard Notes documentation: https://standardnotes.com/help/plugins/themes and https://standardnotes.com/help/plugins/publishing.
