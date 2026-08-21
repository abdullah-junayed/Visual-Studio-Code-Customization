# Visual Studio Code Customization

## 🛠 VS Code Settings

```bash

{
  // Appearance (Your preferences)
  "workbench.colorTheme": "Dark Chai",
  "workbench.iconTheme": "material-icon-theme",
  "window.titleBarStyle": "custom",
  "window.zoomLevel": -0.5,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5,
  "editor.fontFamily": "'JetBrains Mono', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "workbench.activityBar.location": "top", 
  "workbench.editor.showTabs": "multiple", 
  "workbench.sideBar.location": "right",

  // Editor Behavior
  "editor.minimap.enabled": false,
  "editor.formatOnSave": true,
  "editor.hover.delay": 500,
  "editor.renderWhitespace": "none",
  "editor.wordWrap": "on",
  "editor.largeFileOptimizations": true,

  // Save & Privacy
  "files.autoSave": "onFocusChange",
  "telemetry.telemetryLevel": "off",
  "explorer.confirmDelete": false,

  // Windows Terminal
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontSize": 13,

  // WSL Terminal
  "terminal.integrated.defaultProfile.linux": "zsh",
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "/usr/bin/zsh"
    }
  },

  // Add these for even faster experience
  "files.watcherExclude": {
    "**/node_modules/**": true,
    "**/venv/**": true,
    "**/__pycache__/**": true,
    "**/.git/**": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/venv": true,
    "**/dist": true,
    "**/build": true
  },
  "js/ts.tsserver.automaticTypeAcquisition.enabled": false,


  // Emmet & Tailwind
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescriptreact": "typescriptreact"
  },
  "tailwindCSS.includeLanguages": {
    "plaintext": "html",
    "html": "html"
  },
  "html.suggest.html5": true,

  // formatters for languages
  "[python]": {
    "editor.defaultFormatter": "charliermarsh.ruff",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
      "source.fixAll.ruff": "explicit",
      "source.organizeImports.ruff": "explicit"
    }
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[css]": {
    "editor.defaultFormatter": "vscode.css-language-features"
  }
}

```

## ⚙️ VS Code Extension

- Prettier - Code formatted (Prettier)
- ES7+ React/Redux/React-Native snippets (dsznajder)
- Tailwind CSS IntelliSense (Tailwind Labs)
- Python, Python Debugger (Microsoft)
- Ruff (Astral Software astral.sh)
- WSL [If you use windows + wsl] for connect with WSL.

## 🎨 VS Code Themes

- Chai Theme (hitesh choudhary) 👈 IM USING THIS THEME.
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
