# Firefox-userChrome

My personal userChrome/userContent, tailored for [Arc Dark KDE theme](https://github.com/PapirusDevelopmentTeam/arc-kde).

These are fully experimental and hosted here mainly as backups.

## Features

* Minimal mode: tabs, extension icons and controls in address bar are hidden by default. They'll be shown when hovering the address bar. This is to be used with [Tree Style Tab extension](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
* Dark theme in new tab, default error messages (due to connection issue and whatnots) and reader mode (only when dark mode is used). `about:*` pages are darkened too, but haven't been cleaned.
* Themed context menu.
* Colored folders in bookmark menu.
* etc.

## Known issues

* Some context menus do not have hover effect.
* Some disabled context menus can not be differentiated with enabled menus.
* "Get Add-ons" window in `about:addons` is not themed.
* addons.mozilla.org is not themed (it should be part of this to theme it due to the fact that extensions can not tamper with this site).
* Three-dots and bookmark buttons are not hidden in minimal mode (they should, since when hovering them, they will be moved to the left by other icons on the right of the address bar).
