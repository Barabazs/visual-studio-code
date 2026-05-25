### [Visual Studio Code](https://code.visualstudio.com/)

#### Install from GitHub Release

Download the latest `dracula.vsix` from [Releases](https://github.com/Barabazs/visual-studio-code/releases), then:

```bash
code --install-extension dracula.vsix
```

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/Barabazs/visual-studio-code.git ~/.vscode/extensions/theme-dracula
cd ~/.vscode/extensions/theme-dracula
npm install
npm run build
```

#### Activating theme

Run Visual Studio Code. The Dracula Syntax Theme will be available from `File -> Preferences -> Color Theme` dropdown menu.
