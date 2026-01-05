# VS Code PTX Assembly Syntax

Syntax highlighting extension for NVIDIA PTX (Parallel Thread Execution) Assembly language in Visual Studio Code.

## Features

- **Syntax Highlighting**: Comprehensive syntax highlighting for `.ptx` files, making assembly code easier to read and understand.

![Example](https://raw.githubusercontent.com/Albresky/vscode-PTX-Assembly-Syntax/main/images/example.png)

## Development & Build

### Prerequisites

- [Node.js](https://nodejs.org/) (v20 or higher)
- NPM (included with Node.js)
- [vsce](https://github.com/microsoft/vscode-vsce) (Visual Studio Code Extensions CLI) for packaging

```bash
npm install -g @vscode/vsce
```

### Setup

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

### Compilation

To compile the source code:

```bash
npm run compile
```

To watch for changes during development:

```bash
npm run watch
```

### Packaging

To create a VSIX package for installation:

```bash
npm run package
```

This will generate a `.vsix` file (e.g., `vscode-ptx-0.0.1.vsix`) in the root directory.

## Installation

### From VS Marketplace

Download from [Visual Studio | Marketplace](https://marketplace.visualstudio.com/items?itemName=Albresky.vscode-ptx-highlighting)

### From VSIX

1. Build the package using the instructions above or **download `.vsix` from [release page](https://github.com/Albresky/vscode-PTX-Assembly-Syntax/releases)**.
2. Open VS Code.
3. Go to the Extensions view (Ctrl+Shift+X).
4. Click on the "..." (Views and More Actions) menu in the top right corner.
5. Select "Install from VSIX...".
6. Choose the generated `.vsix` file.

Alternatively, we install via command line:

```bash
code --install-extension <PATH_TO_VSIX>
```
