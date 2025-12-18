### Theme `High contrast dark` customization:
Add the to the settings.json

```json
  // Custom (Modify some default themes)
  // These are applied only for High Contrast Dark Theme
  // Collected from different places and personalized
  "workbench.colorCustomizations": {
    "[Default High Contrast]": {
      "contrastBorder": "#0000",
      "contrastActiveBorder": "#777777",
      "editor.lineHighlightBorder": "#0000", // #RGBA
      "editorIndentGuide.background1": "#727272", // Color of normal indent guides (hex with optional transparency)
      "editorIndentGuide.activeBackground1": "#0fff7f", // Color of the active indent guide (where your cursor is)
      "sideBar.border": "#777777",
      "panel.border": "#777777",
      "panelTitle.activeBorder": "#777777",
      // "statusBar.background": "#252525",
      "statusBar.border": "#404040",

      // Integrated Terminal: Material Darker 
      // Themes: https://glitchbone.github.io/vscode-base16-term/#/material-darker
      "terminal.background":"#212121",
      "terminal.foreground":"#EEFFFF",
      "terminalCursor.background":"#EEFFFF",
      "terminalCursor.foreground":"#EEFFFF",
      "terminal.ansiBlack":"#212121",
      "terminal.ansiBlue":"#82AAFF",
      "terminal.ansiBrightBlack":"#4A4A4A",
      "terminal.ansiBrightBlue":"#82AAFF",
      "terminal.ansiBrightCyan":"#89DDFF",
      "terminal.ansiBrightGreen":"#C3E88D",
      "terminal.ansiBrightMagenta":"#C792EA",
      "terminal.ansiBrightRed":"#F07178",
      "terminal.ansiBrightWhite":"#FFFFFF",
      "terminal.ansiBrightYellow":"#FFCB6B",
      "terminal.ansiCyan":"#89DDFF",
      "terminal.ansiGreen":"#C3E88D",
      "terminal.ansiMagenta":"#C792EA",
      "terminal.ansiRed":"#F07178",
      "terminal.ansiWhite":"#EEFFFF",
      "terminal.ansiYellow":"#FFCB6B"
    }
  }
```
