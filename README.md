# Visual Studio Code Customization

## 🛠 VS Code Settings

```bash

{
  // 🖋️ Editor Typography
  "editor.fontSize": 18,
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "editor.lineHeight": 28,
  "editor.wordWrap": "on",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "phase",
  "editor.cursorStyle": "line-thin",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "editor.linkedEditing": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "editor.hover.enabled": "on",
  "editor.smoothScrolling": true,
  "editor.minimap.enabled": true,
  "editor.minimap.size": "fill",
  "editor.minimap.renderCharacters": false,
  "editor.minimap.maxColumn": 80,

  // 🎨 Custom Colors & Theme
  "workbench.colorTheme": "Dark Chai",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.editor.enablePreview": false,
  "editor.tokenColorCustomizations": {
    "comments": "#a29bfe",
    "keywords": "#ff6ac1",
    "functions": "#74b9ff",
    "strings": "#ffeaa7",
    "variables": "#00cec9"
  },

  // 🧠 IntelliSense & Formatting
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.defaultFormatter": "charliermarsh.ruff"
  },

  // 🧪 Prettier Config
  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",

  // 🌐 Terminal
  "terminal.integrated.fontSize": 18,
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "underline",
  "terminal.integrated.fontFamily": "'Fira Code', 'JetBrains Mono', 'Cascadia Code', monospace",

  // 🔥 Live Server & SASS
  "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,

  // 📸 Screencast Mode
  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#f1c40f",
  "screencastMode.verticalOffset": 0,

  // ⚙️ Emmet for JSX
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },

  // 🧼 Misc
  "window.zoomLevel": 0,
  "diffEditor.wordWrap": "on",
  "security.workspace.trust.untrustedFiles": "open",
  "terminal.integrated.fontLigatures.enabled": true,
  "files.autoSave": "afterDelay",
  "editor.mouseWheelZoom": true,
  "workbench.sideBar.location": "right"
}


```

## ⚙️ VS Code Extension

- Auto Close Tag (Jun Han)
- Auto Import - ES6, TS, JSX, TSX (Sergey Korenuk)
- Auto Rename Tag (Jun Han)
- ESLint (Microsoft)
- HTML CSS Support (ecmel)
- JavaScript (ES6) code snippets (charalampos karypidis)
- Live Server (Ritwick Dey)
- npm Intellisense (Christian Kohler)
- Path Intellisense (Christian Kohler)
- Prettier - Code formatted (Prettier)
- ES7+ React/Redux/React-Native snippets (dsznajder)
- Reactjs code snippets (charalampos karypidis)
- Snipped (Jefferson Licet)
- Tailwind CSS IntelliSense (Tailwind Labs)
- Python, Python Debugger and Python Environments (Microsoft)
- Ruff (Astral Software astral.sh)
- Jupyter (Microsoft)
- Fluent Icons (Miguel Solorio)
- GitHub Copilot (GitHub)
- WSL (Microsoft) for connect with wsl distro.

## 🎨 VS Code Themes

- chai theme (hitesh choudhary) 👈 IM USING THIS THEME.
- Material Icon Theme (Philipp Kief)

## 🔑 VS Code Keyboard Shortcuts

| Keyboard Shortcuts                     | Windows / Linux           | Mac                          |
| :------------------------------------- | :------------------------ | :--------------------------- |
| HTML boilerplate                       | ! + TAB                   | ! + TAB                      |
| Open the palette to search for a file  | Ctrl + P                  | cmd + P                      |
| Add cursors to all matching selections | Ctrl + Shift + L          | cmd + Shift + L              |
| Undo                                   | Ctrl + U                  | cmd + U                      |
| Select Current Line                    | Ctrl + L                  | cmd + L                      |
| Zen Mode                               | Ctrl + K Z                | cmd + K Z                    |
| Toggle Sidebar                         | Ctrl + B                  | cmd + B                      |
| Search Global Files                    | Ctrl + Shift + F          | Ctrl + Shift + F             |
| Search on file                         | Ctrl + F                  | cmd + F                      |
| Find and Replace                       | Ctrl + H                  | cmd + H                      |
| Delete the previous Word               | Ctrl + Backspace          | cmd + Backspace              |
| Move line up/Down                      | Alt + up/down arrow       | option + up/down arrow       |
| Add multiple cursors                   | Ctrl + Alt +up/down arrow | cmd + option + up/down arrow |
| Comment Line                           | Ctrl + /                  | cmd + /                      |
| Comment Line                           | Ctrl + K + Ctrl + C       | cmd + K + cmd + C            |
| Split View                             | Ctrl + \                  | cmd + \                      |
| Switch Between views                   | Ctrl +1, Ctrl + 2 ..      | cmd + 1, cmd + 2             |
| Duplicate Line                         | Alt + Shift + up/down     | option + Shift + up/down     |
| Navigate to a specific line            | Ctrl + g                  | cmd + G                      |
| Open Terminal                          | Ctrl + `                  | cmd + `                      |
| To Show suggestion                     | Ctrl + Space              | cmd + space                  |
| To Close a TAB                         | Ctrl + W                  | cmd + W                      |
| To Close all TAB                       | Ctrl + Shift + W          | cmd + Shift + W              |

## ✒ Font Info

- [Fira Code](https://fonts.google.com/specimen/Fira+Code)
- [Operator Mono](https://www.typography.com/fonts/operator/styles)
- [Nerd Fonts](https://www.nerdfonts.com/) for zsh shell theme

## 🧑‍💻 Contributors

- [@Md. Abdullah Junayed](https://github.com/abdullah-junayed)

## 🥰 Follow me

- [@Github](https://github.com/abdullah-junayed)
- [@Facebook](https://web.facebook.com/AbdullahJunayed771/)
