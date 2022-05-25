# vscode-jasmin README

This Visual Studio Code extension provides really basic syntax highlighting
support for the [jasmin](https://github.com/jasmin-lang/jasmin) domain-specific
language for high-assurance assembly programming of cryptographic software.

## Installation

```shell
# Clone the repository and cd into it
git clone https://github.com/dsprenkels/vscode-jasmin
cd vscode-jasmin

# Install dependencies
npm install

# Build an extension package for Visual Studio Code
npx vsce package
```

Now in VSCode, choose `Extensions: Install vrom VSIX...` from the Command
Palette (`Ctrl+Shift+P` by default) and select the package file.

## Features

At this point, the syntax-highlighting support is really rudimentary.
I will expand this extension when the GitHub repo reaches a number of stars.
Some features that I am planning to add:

  * Publish the package in the VSCode
  * Add semantic highlighting (e.g., different colors for parameters vs. local variables)
  * Snippets for `for`/`while` loops
  * "go to definition" support (this is pretty advanced without any kind of
    Language Server for Jasmin, so don't expect this any time soon)

<!--

## Extension Settings

There are currently no extension settings.

## Known Issues

There are currently no known issues.

## Release Notes

There are currently no releases.

### [Unreleased]

Initial release of ...

-->

## Questions

Feel free to open an issue for questions or feature requests.