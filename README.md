# RWSDK Light Theme 🌲

![](https://github.com/redwoodjs/rwsdk-light-ide-theme/blob/main/images/rwsdk-light-theme.png?raw=true)

The RWSDK Light Theme brings RedwoodSDK's warm, earthy branding into your coding environment. With its signature orange (#e47947), rich earth tones, and cream background (#FFFAF3), this theme delivers excellent readability while reducing eye strain during long coding sessions. Perfect for developers who want their VS Code to reflect RedwoodSDK's distinctive brand identity without sacrificing productivity.

## Installation

1. Install your **[Visual Studio Code](https://code.visualstudio.com/)** based IDE of choice (VS Code, Cursor, Windsurf, etc)
2. Launch it
3. Choose **Extensions** from menu
4. Search for **RWSDK**
5. Click Install to install it
6. Click Reload to reload the Code
7. From the menu bar click: **Code > Preferences > Color Theme > RWSDK Light**

## Other Versions

- Hyper
- iTerm2
- Atom
- Alfred
- TextMate
- Sublime Text 3
- Slack

## Separate the Editor from the Sidebar

```json
"workbench.colorCustomizations": {
  "[RWSDK]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  },
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://dank.sh/). Editor settings to activate font ligatures:

```json
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

I use this setting:

```json
"bracketPairColorizer.forceIterationColorCycle": true,
```

## Miscellaneous

If you see something "off", please feel free to file an issue! I'm sure there are things I missed.

Any relevant changes for each version are documented in the [changelog](https://github.com/redwoodjs/rwsdk-light-ide-theme/blob/main/CHANGELOG.md). Please update and check the changelog before [filing any issues](https://github.com/ahaywood/rwsdk-vs-light-code-theme/issues?q=sort:updated-desc+is:issue+is:open), as they may have already been taken care of.

## Acknowledgements

This theme stands on the shoulders on those that have gone before me, borrowing from [Wes Bos's Cobalt2 theme](https://github.com/wesbos/cobalt2-vscode) and [Sarah Drasner's Night Owl theme.](https://github.com/sdras/night-owl-vscode-theme)
