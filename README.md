# vscodeConfig

{
  // Theme VSCode
  "workbench.colorTheme": "FireFly Pro",
  // Font Config
  "editor.fontSize": 11,
  "editor.lineHeight": 24,
  "editor.fontFamily": "fira code light",
  "editor.fontWeight": "500",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 10,
  // Limit line bar
  "editor.rulers": [120],
  "editor.formatOnSave": true,
  "eslint.packageManager": "npm",
  "files.associations": {
    ".sequelizerc": "javascript"
  },
  // Style line select
  "editor.renderLineHighlight": "gutter",
  // Theme icons
  "workbench.iconTheme": "material-icon-theme",
  // Windows and tabs config
  "workbench.startupEditor": "newUntitledFile",
  "editor.tabSize": 2,
  "window.zoomLevel": 0,
  // Config extensions
  "extensions.ignoreRecommendations": true,
  "explorer.compactFolders": false,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  // Editor Configs
  "javascript.updateImportsOnFileMove.enabled": "never",
  "breadcrumbs.enabled": true,
  "git.enableSmartCommit": true,
  "editor.parameterHints.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "terminal.integrated.shell.osx": "/bin/zsh",
  "explorer.confirmDragAndDrop": false,
  "liveshare.featureSet": "insiders",
  "explorer.confirmDelete": false,
  "typescript.tsserver.log": "verbose",
  "javascript.suggest.autoImports": false,
  "typescript.suggest.autoImports": false,
  "workbench.activityBar.visible": true,
  "prettier.jsxSingleQuote": false,
  "prettier.singleQuote": true,
  // ESLint TSLink + Plugin Prettier
  "editor.codeActionsOnSave": {
    // For ESLint
    "source.fixAll.eslint": true,
    // For TSLint
    "source.fixAll.tslint": true,
    // For Stylelint
    "source.fixAll.stylelint": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // VueJs + Vetur
  "vetur.format.defaultFormatter.js": "vscode-typescript",
  // "vetur.format.defaultFormatter.html": "js-beautify-html",
  "vetur.validation.template": false,
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "liveServer.settings.donotShowInfoMsg": true,
  "workbench.sideBar.location": "left"
}
