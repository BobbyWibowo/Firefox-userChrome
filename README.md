# Firefox-userChrome

My personal userChrome/userContent, tailored for [Materia Dark KDE theme](https://github.com/PapirusDevelopmentTeam/materia-kde) or just dark UI in general (also works fine in Windows).

These are fully experimental and hosted here mainly as backups.

## Features

* Minimal mode. Only pinned tabs and active tab will be visible above URL bar (native Title Bar must be disabled). This is to be used with [Tree Style Tab extension](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
* Auto-hide sidebar when fullscreen (intended to auto-hide Tree Style Tab sidebar).
* Auto-hide sidebar when there's only 1 active tab (intended to auto-hide Tree Style Tab sidebar; unfortunately requires [Tab Count in Window Title extension](https://addons.mozilla.org/en-US/firefox/addon/tab-count-in-window-title/)).
* Various tweaks to Tree Style Tab sidebar itself ([TreeStyleTab.css](#treestyletabcss))
* Dark theme in built-in home and new tab pages, GitHub raw files, local files, blank pages (matches Firefox's built-in dark color scheme).
* Find bar (Ctrl+F) moved to the top.
* Removed URL bar's background and borders.
* etc.

## To-do(s)

* Update dark color scheme for Reader mode (currently using an old color scheme based on Arc-Dark).

## TreeStyleTab.css

Open Tree Style Tab's preferences through Add-ons > Tree Style Tab > Preferences.

Enable **Proton** theme in Appearance > Theme.

Then use the content of CSS file in Advanced > Extra style rules for contents provided by Tree Style Tab.
