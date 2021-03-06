# DSC GEN

<p align="center">
  <img src="https://img.shields.io/npm/v/dscgen?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/TheOfficialDev-ops/dscgen?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/TheOfficialDev-ops/dscgen?style=for-the-badge">
  <img src="https://img.shields.io/discord/582319490122121247?style=for-the-badge">
</p>

<p align="center">Create a discord bot in seconds!</p>

## What is DSC GEN?

DSC GEN is a CLI (Command Line Interface) that lets you generate Discord.JS Bots in seconds!

## Why DSC GEN?

Do you use a Command/Event Handler? Are you tired of having to copy & paste the same files over and over again, or cloning a repository? DSC GEN serves as a purpose to eliminate the annoyance of doing that. Instead, with a simple command, DSC GEN will generate a base structure for your next Discord Bot Project.

It does so by using the most basic command & event handler. Simplicity is key. And since it works well, why change it? Regardless, if you need to try some things out without needing to re-write the same functions all the time, DSC GEN is great for that.

It also eliminates the abstraction away from users so they need not worry about how commands and events are registered. It will just work out of the box.

## What DSC GEN is NOT

- Framework
- Library
- Discord Bot (It is a Discord Bot Project **generator**)
- Replacement for coding

# Getting Started

Install DSC GEN by running `npm install -g dscgen` or `yarn global add dscgen` on your terminal or Windows CMD. This will install DSC GEN globally.

- To create a project, type `dscgen`, or simply type `dscgen new <name of project>` in your Terminal or Command Prompt.
- Follow the steps and enter your Bot Token and Prefix.
- Once done, `cd` into your project by typing `cd <name of project>`
- To run the bot, type `npm run dev` or `yarn dev`. This will run the bot using `nodemon` which is installed locally.

## Generating Commands

- DSC GEN allows you to generate commands into categories. You can type `dscgen` and select **Generate** to generate a command, or `dscgen gen command`.
- It will ask you for a name, and then a category. This will generate all commands in the `src/commands` folder, in the correct category.
- You can also generate a command by typing `dscgen gen command`. This will prompt you for a command name and category.

## Generating Events

- You can generate events by running `dscgen gen event`, this will prompt you to select which events you would like to generate.
- To select event(s), press space bar and use the up and down arrow keys to navigate. Hit enter when you're done and your event files will be generated in the `src/events` folder.

## Will DSC GEN support TypeScript?

**YES!** DSC GEN now supports typescript!

~~You must have TypeScript installed. However, if you don't, during the installation process, if you selected TypeScript, DSC GEN will ask you if you would like to install TypeScript, ts-node, and setup a basic tsconfig.json file. If you enter n (no), you will have to install these manually.~~

~~ts-node is a TypeScript interpreter for Node.JS, the dev script uses it along with nodemon, so be sure you have nodemon installed.~~

~~Otherwise, if you have TypeScript installed, you can skip this part and just run `npm run build` and then `npm run start`~~

## Will DSC GEN support Python?

Not yet. But this is a planned update on the future.

# Recipes

### Integrating with Sequelize

```
Implementation Provided Soon
```

### Integrating with Mongoose

```
Implementation Provided Soon
```

### Integrating with QuickDB

```
Implementation Provided Soon
```

### Integrating with Lavalink

```
Implementation Provided Soon
```

### Note: DSC GEN Is an upgraded fork of [SLAPPEY](https://github.com/stuy/slappey)
Original Base Credits go to the developer of SLAPPEY.
