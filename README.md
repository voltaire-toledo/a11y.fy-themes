# VTG Theme Pack (tg.pub-vscode-themes)

A curated, unified theme pack extension for VS Code & VS Code Insiders maintained by Voltaire Toledo.

## Included Themes
- **Pink Cat Boo (Tuned)**: Customized dark theme with optimized contrast and accents.

## Development & Testing Workflow
1. Open this repository in VS Code / VS Code Insiders:
   ``bash
   code .
   ``
2. Press F5 to launch an **Extension Development Host** to preview color changes live.
3. Use Ctrl+Shift+P -> Developer: Inspect Editor Tokens and Scopes to inspect syntax tokens.

## Building and Packaging
To package as a .vsix for direct installation across machines:
``bash
npx @vscode/vsce package
``
To install the generated .vsix:
``bash
code --install-extension vtg-pub-vscode-themes-0.1.0.vsix
``
