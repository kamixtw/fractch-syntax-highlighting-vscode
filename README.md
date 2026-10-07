# Fractch Syntax Highlighting for VS Code

A Visual Studio Code extension that provides syntax highlighting for the [Fractch DSL](https://github.com/mistium/FRACTCH).

## Features

- Syntax highlighting for `.fractch` files
- Support for comments (`//` line comments and `/* */` block comments)
- Highlighting for Fractch keywords, control flow, variables, operators, and strings
- Template literal support with interpolation
- Triple-quoted raw strings

## Installation

1. Clone this repository
2. Run `npm install` in the extension directory
3. Run `vsce package` to create a `.vsix` file
4. Install the `.vsix` file in VS Code: `Extensions > ... > Install from VSIX...`

Or install from the VS Code marketplace (when published).

## Usage

Open any `.fractch` file and the syntax highlighting will be applied automatically.

## License

Apache-2.0
