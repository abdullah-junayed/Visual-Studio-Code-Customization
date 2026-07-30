# Visual Studio Code Customization

## 🛠 VS Code Settings

```bash

{
  // --- 1. THEME & MODERN AESTHETIC ---
  "workbench.colorTheme": "Dark Chai",
  "workbench.iconTheme": "material-icon-theme",
  "window.titleBarStyle": "custom", // Looks much cleaner on Windows 11
  
  // --- 3. 14-INCH SCREEN @ 150% SCALE OPTIMIZATIONS ---
  // Shrinks the bulky UI (sidebar/tabs) but keeps the code font large and readable
  "window.zoomLevel": -0.5,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "editor.minimap.enabled": false, // Essential for saving space on a 14-inch screen
  "editor.stickyScroll.enabled": true,
  "editor.fontFamily": "'JetBrains Mono', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "editor.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",

  // --- 4. LANGUAGE SPECIFIC CONFIGS ---
  // Python & Data Science
  "[python]": {
    "editor.defaultFormatter": "charliermarsh.ruff",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
      "source.fixAll.ruff": "explicit",
      "source.organizeImports.ruff": "explicit",
    },
  },
  "notebook.lineNumbers": "on",
  
  // JS / TS / React / Next.js
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  
  // HTML / CSS / PHP
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
  },
  "[css]": {
    "editor.defaultFormatter": "vscode.css-language-features",
  },
  "[php]": {
    "editor.defaultFormatter": "bmewburn.vscode-intelephense-client",
  },
  
  // C / C++ / Java
  "[cpp]": {
    "editor.defaultFormatter": "ms-vscode.cpptools",
  },
  
  // DevOps & Data
  "[sql]": {
    "editor.formatOnSave": true,
  },
  "sqltools.results.location": "pane",
  
  // --- 5. TERMINAL & WSL ---
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.gpuAcceleration": "auto", // Better stability for laptop battery/APU
  "terminal.integrated.cursorBlinking": true,
  
  // --- 6. AUTOMATION & MODERN UI ---
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.linkedEditing": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1000,
  "editor.hover.delay": 300,
  "explorer.confirmDelete": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescriptreact": "typescriptreact",
  },
}


```

## ⚙️ VS Code Extension

- c/c++ (Microsoft)
- PHP Intelephense (Intelephense)
- Live Server (Ritwick Dey)
- Prettier - Code formatted (Prettier)
- ES7+ React/Redux/React-Native snippets (dsznajder)
- Tailwind CSS IntelliSense (Tailwind Labs)
- Python, Python Debugger and Python Environments (Microsoft)
- Ruff (Astral Software astral.sh)
- TODO Highlight (Wayou Liu)
- Docker DX (Docker)
- Live Share (Microsoft)
- WSL [If you use windows + wsl] for connect with WSL.

## 🎨 VS Code Themes

- Chai Theme (hitesh choudhary) 👈 IM USING THIS THEME.
- indent-rainbow (oderwat)
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
