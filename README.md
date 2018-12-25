# (Pub)lisher :rocket:

[![Issues](https://img.shields.io/github/issues/1337z/lisher.svg)](https://github.com/1337z/lisher/issues) [![Forks](https://img.shields.io/github/forks/1337z/lisher.svg)](https://github.com/1337z/lisher/fork) [![Stars](https://img.shields.io/github/stars/1337z/lisher.svg)](https://github.com/1337z/lisher/stargazers) [![License](https://img.shields.io/github/license/1337z/lisher.svg)](LICENSE)

> Simple package publisher/releaser for your projects with live output!

## :star: Features

![Preview](https://i.imgur.com/wJnWbSW.gif)

Pub`lish` your module to NPM, GIT and VSCE with a single command.  
You can choose where you want your module to be published.  
Lisher will detect task managers as grunt and will ask you to run them before publishing!  
You forgot to commit your changes? Don't worry, lisher will notify you and if you want you can also set the commit message in lisher itself for an even faster publication.

### Publish providers

- GIT
- NPM (Node Package Manager)
- VSCE (Visual Studio Code Extension [Marketplace])
- Want more? Send an [issue](https://github.com/1337z/lisher/issues/new) or [pull request](https://github.com/1337z/lisher/pulls) :)

### Detections

- Detect GIT repository
  - Detect unstaged changes
  - Commit unstaged changes (we will ask you first)
- Detect NPM module
- Detect VS Code extension
- Detect Gruntfile
- Want more? Send an [issue](https://github.com/1337z/lisher/issues/new) or [pull request](https://github.com/1337z/lisher/pulls) :)

## :package: Install

```command
> npm i -g lisher
```

## :clipboard: Usage

> Simply run this command in your project directory. It will start the publish wizard :sparkles:

```command
> lisher
```

### Task managers

#### Grunt

If `lisher` detects a _Gruntfile_, it will ask you to run Grunt for you before publishing the module. If you select __Yes__ (standard selection) `lisher` will run Grunt for you.

### Publish to a git repository

> If you have uncommited files, it's good to commit them before publishing the project. Lisher will ask you to do so if you haven't already.  
> __Notice:__ When you commit your changes via the `lisher` interface you won't be able to set a commit __message body__ for the sake of fast publishing.

1. First of all start Lisher

```command
> lisher
```

2. Select `GIT`
3. Follow the instructions given by the terminal

### Publish to NPM

> If you have uncommited files, it's good to commit them before publishing the project. Lisher will ask you to do so if you haven't already.  
> __Notice:__ When you commit your changes via the `lisher` interface you won't be able to set a commit __message body__ for the sake of fast publishing.

1. First of all start Lisher

```command
> lisher
```

2. Select `NPM`
3. Follow the instructions given by the terminal

### Publish to the Visual Studio Code Marketplace

> If you have uncommited files, it's good to commit them before publishing the project. Lisher will ask you to do so if you haven't already.  
> __Notice:__ When you commit your changes via the `lisher` interface you won't be able to set a commit __message body__ for the sake of fast publishing.

1. First of all start Lisher

```command
> lisher
```

2. Select `VSCE`
3. Follow the instructions given by the terminal

## :clapper: Preview

### _Outdated!_

<details>
<summary>GIT</summary>

### GIT

![Preview GIT](https://i.imgur.com/CLg5uFW.gif)

#### GIT with dirty working directory

![Preview GIT dirty workdir](https://i.imgur.com/MXi6KJE.gif)

</details>

<details>
<summary>Grunt</summary>

### Grunt task manager

![Preview Grunt](https://i.imgur.com/8SASVLE.gif)

</details>

<details>
<summary>NPM</summary>

### NPM & GIT

![Preview NPM](https://i.imgur.com/fKOa0mv.gif)

</details>

<details>
<summary>VSCE</summary>

### VSCE & GIT

![Preview VSCE](https://i.imgur.com/ljn4bti.gif)

</details>
