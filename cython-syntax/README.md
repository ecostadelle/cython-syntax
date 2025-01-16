# Cython Syntax Highlighting Fixed

This package provides syntax highlighting for Cython code. It is based on Peter Varo's [TextMate](https://github.com/petervaro/python) bundle.

This is an updated version of the Cython syntax highlighting extension by Thomas Walther, available at [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=tcwalther.cython). It includes bug fixes and improved compatibility for Linux platforms, ensuring better support across all environments.

## Features

- Syntax highlighting for Cython files (`.pyx`, `.pxi`, `.pxd`).
- Bug fixes for Linux compatibility (case sensitivity).
- Updated comment style to Python (`#`).
- Modernized metadata and prepared for long-term maintenance.

## Installation

1. Install the extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/vscode).
2. Alternatively, download the `.vsix` file from [Releases](https://github.com/ecostadelle/cython-syntax/releases) and install it manually:
   ```bash
   code --install-extension cython-syntax-fixed-1.0.0.vsix
   ```

## Usage

Once installed, the extension will automatically activate for files with the following extensions:
- `.pyx`
- `.pxi`
- `.pxd`

To use this extension, open any Cython file, and syntax highlighting will be applied.

## Contributing

Contributions are welcome! If you encounter any issues or have ideas for improvement, feel free to open an issue or submit a pull request at [GitHub](https://github.com/ecostadelle/cython-syntax).

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

## Note 

This package does not provide any Intellisense, just syntax highlighting.