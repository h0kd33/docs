# Quick Start

## Installation

Make sure [Nodejs v6.5+](https://nodejs.org) has been installed correctly.

We recommend that you create and publish your game using our command-line tools:

```shell
npm install -g avg-cli
avg create mygame
```

You will be asked to enter the project name (folder name) and the game name, the final output is similar to:

```
$ avg create mygame
? What's your project name? mygame
? What's your game name? My Game
? Your game project will be created at /Users/username/mygame 
continue? Yes
[INFO]  Please make sure you have access to github.com to download the latest template package
✔ Downloading the latest template...
✔ Unzipping...
✔ Initializing...
[INFO]  Your project has been created!
[INFO]  Run `cd mygame && npm run dev` to have a quick look.
```

## Start Development

```shell
cd mygame
npm run dev
```

调试服务器将启动，并弹出浏览器页面

这时可以用任何代码编辑器打开 mygame 文件夹下的文件，开始修改模板工程，使之成为你的游戏项目。

每当你修改了文件并按下保存，浏览器中的画面将自动更新或刷新。

## Publish Game

```shell
avg publish
```

Publishing process will begin automatically. Finally, you can find the full release game in the `./dist` folder. You can upload it to your server or start a local server to play.

