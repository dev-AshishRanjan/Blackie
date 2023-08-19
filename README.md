![Blackie](https://socialify.git.ci/dev-AshishRanjan/Blackie/image?description=1&descriptionEditable=Introducing%20Blackie%2C%20a%20cutting-edge%20solution%20that%20merges%20advanced%20browser%20technology%20and%20meticulous%20measurement%20strategies&font=KoHo&forks=1&issues=1&language=1&owner=1&pattern=Plus&pulls=1&stargazers=1&theme=Auto)

<div align="center">
 <p>
   
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)
![Visitors](https://api.visitorbadge.io/api/visitors?path=dev-AshishRanjan%2FBlackie%20&countColor=%23263759&style=flat)
![GitHub forks](https://img.shields.io/github/forks/dev-AshishRanjan/Blackie)
![GitHub Repo stars](https://img.shields.io/github/stars/dev-AshishRanjan/Blackie)
![GitHub contributors](https://img.shields.io/github/contributors/dev-AshishRanjan/Blackie)
![GitHub last commit](https://img.shields.io/github/last-commit/dev-AshishRanjan/Blackie)
  
![GitHub repo size](https://img.shields.io/github/repo-size/dev-AshishRanjan/Blackie)

![Github](https://img.shields.io/github/license/dev-AshishRanjan/Blackie)
![GitHub issues](https://img.shields.io/github/issues/dev-AshishRanjan/Blackie)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/dev-AshishRanjan/Blackie)
![GitHub pull requests](https://img.shields.io/github/issues-pr/dev-AshishRanjan/Blackie)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/dev-AshishRanjan/Blackie)

 </p>
</div>

---

# Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View -> Extensions`
2. Search for `Blackie`
3. Click on **Blackie**
4. Click **Install** to install it
5. Click **Reload** to reload the editor
6. Code > Preferences > Color Theme > **Blackie**

---

# Theme Preview

Here are some pics showcasing the **_Blackie_** Theme

| DARK                 |
| -------------------- |
| ![1](./images/1.png) |
| ![2](./images/2.png) |
| ![3](./images/3.png) |
| ![4](./images/4.png) |
| ![5](./images/5.png) |

---

# Development

Steps to create a new theme in VS Code

## 1. install yo

```
npm install -g yo
```

## 2. Install generator (we are using code)

```
npm install generator-code -g
```

## 3. Initilize a code using yo

```
npx yo code
```

This command will guide you through setting up your extension, including selecting the theme type.

## 4. Develop Your Theme

Open the project folder in your preferred code editor.
Navigate to the `themes` folder in your project directory. This is where you'll define your theme's color scheme and styling.
Edit the `.json` file in the `themes` folder to define the color scheme and other theme-related settings. You can also use a tool like "Theme Color Picker" in VS Code to help you design the color palette.

## 5. Test your Theme

use `F5` to start a dev vscode.
There Select your theme.
To change your theme in the new vscode window use `CTRL + K` + `CTRL + T`. Now a list of themes appear, select your development theme, it's shown there.

## 6. Publish

```
vsce login <publisher_id>
```

```
vsce publish
```

If You're facing the **proxy** problem 
then use this command: `vsce package`
and then upload it manually from vsix file on marketplace

All code in CLI or Terminal

---

## For more information

- [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
- [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
