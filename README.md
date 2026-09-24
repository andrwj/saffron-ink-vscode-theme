# Saffron Ink

A warm, high-contrast light theme for Visual Studio Code, inspired by saffron paper and crisp ink.

Saffron Ink is designed for long reading and writing sessions: a soft paper-toned editor background, dark readable text, restrained UI chrome, and clear selection feedback.

Saffron Ink is based on `Github Light Theme - Gray` from the Visual Studio Code extension `hyzeta.vscode-theme-github-light`.

## Preview

![Saffron Ink editor preview](https://raw.githubusercontent.com/andrwj/saffron-ink-vscode-theme/main/screenshot1.png)

![Saffron Ink workspace preview](https://raw.githubusercontent.com/andrwj/saffron-ink-vscode-theme/main/screenshot2.png)

## Features

- Warm light editor background with strong text contrast.
- Dark, readable Markdown and code token colors.
- High-visibility selection colors tuned for the saffron palette.
- Subtle workbench borders and scrollbar styling.
- Compact workbench density by default.

## Installation

Search for `Saffron Ink` in the Visual Studio Code Extensions view, then select **Install**.

After installation, open the Command Palette and run:

```text
Preferences: Color Theme
```

Then choose **Saffron Ink**.

## Manual Install

If you have a packaged `.vsix` file, install it from the command line:

```sh
code --install-extension saffron-ink-0.2.1.vsix
```

If the `code` command is not available, open VS Code and run
`Shell Command: Install 'code' command in PATH` from the Command Palette.

## Development

Install dependencies and package the extension:

```sh
npm install
npm run package
```

During local theme development, this repository can be linked directly into VS Code's extensions directory:

```sh
ln -s "$(pwd)" "$HOME/.vscode/extensions/andrwj.saffron-ink-0.2.1"
```

After editing theme files, run `Developer: Reload Window` in VS Code.

## Repository

https://github.com/andrwj/saffron-ink-vscode-theme

## Credits

Saffron Ink is derived from `Github Light Theme - Gray`, distributed as part of the `hyzeta.vscode-theme-github-light` Visual Studio Code extension.

The original theme license notice is preserved in this repository. The original MIT license identifies:

```text
Copyright 2020 Ling CHU <meetchuling@outlook.com>
```

## License

MIT. This project preserves the original MIT license notice from the source theme.
