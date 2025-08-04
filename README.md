# My VSCODE Settings ✨

```json title="settings.json"
{
  // General settings
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "symbols",
  "workbench.colorTheme": "GitHub Dark Default",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.editorAssociations": {
    "{git,gitlens}:/**/*.{md,csv}": "default",
    "{git,gitlens}:/**/*.{md,csv,svg}": "default"
  },
  "workbench.sideBar.location": "right",
  "workbench.tree.enableStickyScroll": false,
  "workbench.tree.renderIndentGuides": "none",
  "workbench.tree.indent": 12,

  // Change the labels of the editor tabs
  "workbench.editor.customLabels.patterns": {
    "**/types/**": "${filename} - Types",
    "**/components/**": "${filename} - Components",
    "**/pages/**": "${filename} - Pages",
    "**/styles/**": "${filename} - Styles",
    "**/utils/**": "${filename} - Utils",
    "**/services/**": "${filename} - Services",
    "**/hooks/**": "${filename} - Hooks",
    "**/contexts/**": "${filename} - Context",
    "**/assets/**": "${filename} - Assets",
    "**/public/**": "${filename} - Public",
    "**/config/**": "${filename} - Config",
    "**/constants/**": "${filename} - Constants",
    "**/handlers/**": "${filename} - Handlers"
  },

  // Terminal settings
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontFamily": "Hack Nerd Font",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.enableImages": true,
  "terminal.integrated.suggest.enabled": true,

  // Editor settings
  "editor.fontFamily": "Hack Nerd Font",
  "editor.tabSize": 2,
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.renderWhitespace": "all",
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  "editor.guides.bracketPairs": true,
  "editor.wordWrap": "on",
  "editor.accessibilitySupport": "off",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "[html][astro][javascript][javascriptreact][typescript][typescriptreact][json][jsonc]": {
    "editor.defaultFormatter": "biomejs.biome"
  },
  "[astro]": {
    "editor.defaultFormatter": "astro-build.astro-vscode"
  },
  "[xml]": {
    "editor.defaultFormatter": "redhat.vscode-xml"
  },
  "[markdown]": {
    "editor.wordWrap": "on"
  },

  // Explorer settings
  "explorer.compactFolders": false,

  "window.menuBarVisibility": "compact",
  "window.newWindowProfile": "JS/TS Development",

  // Git Client
  "git.autofetch": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,

  // For GitHub Copilot Extension
  "github.copilot.editor.enableAutoCompletions": true,
  "github.copilot.nextEditSuggestions.enabled": true,
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },

  // Import Updates on File Move Settings
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "security.workspace.trust.untrustedFiles": "open",

  // Symbols Extension Settings
  "symbols.hidesExplorerArrows": true,

  // Auto Close Tag Extension
  "auto-close-tag.activationOnLanguage": [
    "xml",
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "plaintext",
    "markdown",
    "HTML (Eex)",
    "astro"
  ],

  // Biome Formatter
  "biome.suggestInstallingGlobally": false
}
```
