# Funky Monky Base Repository

## Introduction

> OOOO AAAA OOOO AAAA

> **This project remains under heavy development and is not recommended for use within another project yet. Yes, the irony is apparent to me. If you would like to contribute, or make a suggestion, create a PR or issue on github, respectively. Feel free to contact me (@CHATALOT1) if you would like to learn more about the project or contribute to it's development.**

This repo is for a work-in-progress fully-functioning but purpose-neutral discord bot complete with a backend API for centralised database interaction and a web dashboard frontend. All three of these components can be neatly controlled using a simple CLI and configured using system environment variables or the .env files.

This bot has a massive and core focus on extensibility for use in more specific bots, but please bare in mind the [license restrictions](#license). This bot is used as a base for all public bots made by Funky Monky Development.

It is distributed under the [GNU Affero General Public License v3.0 (GNU AGPLv3)](LICENSE) (see [below](#license))

## Table of Contents

- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Legacy](#legacy)
- [License](#license)

## Installation

**Be sure to read [about the license](#license)**

**DETAILS ON INSTALLING AND CONFIGURING THIS PROJECT ARE TO BE ADDED HERE SOON. ONCE THE PROJECT HAS A SOLID ENOUGH SKELETON FOR ME TO TRUST MYSELF NOT TO CHANGE IT ALL ON A WHIM, THIS SECTION WILL BE UPDATED.**

## Legacy

This project is based partially on [this (now-archived) project](), intended to serve the same purpose but with a smaller scope. Among the reasons for the re-starting of the project and transition to this repo are:

- discord.py stopping maintenance and development, the details and reasoning of which are outlined by the project's creator, [here](https://gist.github.com/Rapptz/4a2f62751b9600a31a0d3c78100287f1).
- The aforementioned huge increase in scope (The project now strives to be more than just a discord bot, but to be a full extensible application with a web frontend and CLI (See [the introduction above](#introduction))
- Large changes being made to the discord API

## License

This bot is licensed under the GNU Affero General Public License v3.0 (GNU AGPLv3). For full legalese see the [license file](LICENSE), or alternatively see the [tl;drLegal page](<https://tldrlegal.com/license/gnu-affero-general-public-license-v3-(agpl-3.0)>)

The important thing to note is that if you are self-hosting the software and making absolutely no changes to the source code (editing the .env files is obviously fine), you are legally safe. However, **if you change the bot's source code, you must open-source your version under the same license. In this case, you must also state all changes you have made publicly.** For more information, read up about the license through one of the aforementioned sources.
