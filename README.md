# JSTris Bot but usable outside practice

<p align="center">
  <image src="public/icon128.png"></image>
</p>

![](https://img.shields.io/github/v/release/vanflux/jstetris-bot)
![](https://img.shields.io/github/actions/workflow/status/vanflux/jstetris-bot/full.yml?branch=main)

Integration of [tetris-ai](https://github.com/vanflux/tetris-ai) with JSTris website.

*I'm not responsible by your actions and consequences! You (probably) will be banned!*

 DON'T play only on practice mode.

Based on [web-game-hacking-boilerplate](https://github.com/vanflux/web-game-hacking-boilerplate.git).


# Note: Releases are still being compiled

## Chrome

- Download latest release `jstris-bot-chrome-multiplayer.zip`
- Unzip to some location on your PC
- Go to url `chrome://extensions`
- Enable development mode
- Load the uncompressed extension and pick the unzipped directory

## Firefox

- Download latest release `jstris-bot-firefox-multiplayer.zip`
- Go to url `about:debugging`
- Go to `This Firefox`
- Load temporary add-ons and pick the .zip

# Development

## Setup + Run

- Clone repo
- Install dependencies: `npm i`
- Run `npm start <chrome|firefox>`

## Chrome

- Go to url `chrome://extensions`
- Enable development mode
- Load the uncompressed extension and pick the `build/dev` directory inside project dir
- If you want the extension hot-reloading working properly open the extension console(`service worker`) and keep it opened on background.

## Firefox

- Go to url `about:debugging`
- Go to `This Firefox`
- Load temporary add-ons and pick the `build/dev` directory inside project dir

# Demo

<p align="center">
  <image src="gifs/demo1.gif"></image>
</p>
