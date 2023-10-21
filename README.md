# JS/TS Monorepos

- [JS/TS Monorepos](#jsts-monorepos)
  - [What's this course about?](#whats-this-course-about)
  - [Project setup](#project-setup)
    - [Tools](#tools)
    - [Clone](#clone)
    - [Install dependencies](#install-dependencies)
    - [Starting the project](#starting-the-project)
  - [Legal](#legal)
  - [Licensing](#licensing)

## What's this course about?

This course is intended teach those already somewhat familiar with modern 
JavaScript and TypeScript about monorepos, their use cases and related tools.

> **Note:** This material used here is from Mike North course on Frontend Master <https://frontendmasters.com/courses/monorepos/>.

## Project setup

First, you should ensure you have [your ssh keys working with GitHub](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). You can verify this by running

```sh
ssh git@github.com
```

and getting a response like

```sh
Hi Mo Elzanaty! You've successfully authenticated, but GitHub does not provide shell access.
Connection to github.com closed.
```

### Tools

Next, make sure you have installed [volta](http://volta.sh/) which ensures you have the right version of node and yarn for this project. You can run:

```shell
volta install node
```

and then:

```shell
volta install yarn
```

To get the right versions for this workshop.

We also strongly recommend the use of [Visual Studio Code](https://code.visualstudio.com/) as an authoring tool. If you use something else, you're on your own.

### Clone

Next, checkout a working copy of this project

```sh
git clone git@github.com:moelzanaty3/js-ts-monorepos
```

enter the directory you just created

```sh
cd js-ts-monorepos
```

### Install dependencies

[`yarn`](https://yarnpkg.com/) is the recommended package manager to use with this project. Please use it instead of npm.

Install dependencies with yarn by running

```sh
yarn
```

### Starting the project

Start up the project in development mode by running

```sh
yarn dev
```

Changing any files in the `src` folder will result in an incremental rebuild, and a refresh of the screen.

By default, the app is served on <https://localhost:1234>.

## Legal

&copy; 2020 LinkedIn, All Rights Reserved

## Licensing

The code in this project is licensed as [BSD-2-Clause](https://opensource.org/licenses/BSD-2-Clause) license, and the written content in the ./notes folder is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
