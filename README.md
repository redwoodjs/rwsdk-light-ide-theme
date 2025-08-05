# RWSDK VS Code Theme 🌲

![]()

A Visual Studio Code theme for developers that like to write code quickly. Color choices have taken into consideration what is accessible to people with colorblindness and in low-light circumstances. Decisions were also based on meaningful contrast for reading comprehension and optimized with sparkle and shine. ✨

## Installation

1. Install your **[Visual Studio Code](https://code.visualstudio.com/)** based IDE of choice (VS Code, Cursor, Windsurf, etc)
2. Launch it
3. Choose **Extensions** from menu
4. Search for **RWSDK**
5. Click Install to install it
6. Click Reload to reload the Code
7. From the menu bar click: **Code > Preferences > Color Theme > RWSDK**

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
  "[RWSDK (No Italics)]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  }
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://dank.sh/). Editor settings to activate font ligatures:

```json
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

The preview image is using [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer), a really cool extension that highlights matching brackets. This can help reduce unwanted errors.

I use this setting:

```json
"bracketPairColorizer.forceIterationColorCycle": true,
```

![]()

## Miscellaneous

If you see something "off", please feel free to file an issue! I'm sure there are things I missed.

Any relevant changes for each version are documented in the [changelog](./CHANGELOG.md). Please update and check the changelog before [filing any issues](https://github.com/ahaywood/RWSDK-VS-Code-Theme/issues?q=sort:updated-desc+is:issue+is:open), as they may have already been taken care of.

## Acknowledgements

This theme stands on the shoulders on those that have gone before me, borrowing from [Wes Bos's Cobalt2 theme](https://github.com/wesbos/cobalt2-vscode) and [Sarah Drasner's Night Owl theme.](https://github.com/sdras/night-owl-vscode-theme)
