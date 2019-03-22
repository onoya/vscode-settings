# VS Code Settings

My Visual Studio Code Settings.

## How to sync settings (Mac)

Remove current VSCode `User` directory:

```bash
rm -rf ~/Library/Application\ Support/Code/User
```

Clone the repository and run the command below:

```bash
ln -s "$(pwd)/vscode-settings" ~/Library/Application\ Support/Code/User
```

## Recommended Extensions

- ES7 React/Redux/GraphQL/React-Native snippets
- PHP Intelephense
- GitLens — Git supercharged
- Prettier - Code formatter
- Path Intellisense
- Node.js Modules Intellisense
- phpcs
- ESLint
- Bracket Pair Colorizer
- markdownlint
- Docker
- Code Runner
- Live Server
- TSLint

Run the commands below to install all my recommended extensions:

*Note: Make sure that you have [installed **code** command in PATH](https://code.visualstudio.com/docs/setup/mac) before running the command below.*

```sh
code \
--install-extension dsznajder.es7-react-js-snippets \
--install-extension bmewburn.vscode-intelephense-client \
--install-extension eamodio.gitlens \
--install-extension esbenp.prettier-vscode \
--install-extension christian-kohler.path-intellisense \
--install-extension leizongmin.node-module-intellisense \
--install-extension ikappas.phpcs \
--install-extension dbaeumer.vscode-eslint \
--install-extension CoenraadS.bracket-pair-colorizer \
--install-extension DavidAnson.vscode-markdownlint \
--install-extension PeterJausovec.vscode-docker \
--install-extension formulahendry.code-runner \
--install-extension ritwickdey.LiveServer \
--install-extension ms-vscode.vscode-typescript-tslint-plugin
```
