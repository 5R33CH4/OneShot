<p align="center">
  <img width="200" height="200" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/Icon.png">
</p>

# OneShot [![TravisCI Status](https://travis-ci.org/5R33CH4/OneShot.svg?branch=master)](https://travis-ci.org/5R33CH4/OneShot) [![Appveyor Status](https://ci.appveyor.com/api/projects/status/qtxvaliwymvhxiwx/branch/master?svg=true)](https://ci.appveyor.com/project/5R33CH4/OneShot)


> 🎯 Adjustable gaming Crosshair Overlay for any screen

OneShot allows you to place a customizable crosshair overlay above any application window.
Improve your aim and gain a competitive advantage with a permanant colored crosshair to mark center screen.


# Quick Start

### [Download OneShot for Windows](https://github.com/5R33CH4/OneShot/releases/latest/download/OneShot.exe)

- Choose a crosshair from over 50 sights
- Click and drag the grip icon to move OneShot around
- Use <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd> and arrow keys for fine-tuning
- <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>X</kbd> to lock in place
- <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>R</kbd> to reset and recenter


## Features

- Choose from tons of true-to-life sights
- Cross-platform: Windows, MacOS, and Linux support
- Support for multiple monitors
- Choose between center **Dot** or **Crosshair**
- Customize crosshair size, color, and opacity
- Persistant settings remembers your choices automatically
- Automatically updates in the background to keep your features fresh
- Tested via Spectron

### [Download OneShot](https://github.com/5R33CH4/OneShot/releases/latest)

<p align="center" style="background:#282a36;box-shadow: 3px 3px 15px 2px rgba(40,42,54,1);">
  <img width="504" height="288" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/demo.png">
</p>

Other crosshair programs offer a single style or color option, and often don't allow you to reposition them. OneShot is a small, unintrusive crosshair overlay which has plenty of configuration options to assist with aiming and vision of your crosshair. OneShot offers a huge improvement to many games' default crosshairs for those with colorblindness or contrast issues.

###### _Thanks to Reddit user /u/IrisFlame for the premade library of crosshairs!_

---

## Install

*Windows 7+ are supported.*

#### Download the latest version of OneShot from the [releases page](https://github.com/5R33CH4/OneShot/releases/latest)

**Windows**

[**Download**](https://github.com/user/repo/releases/latest/download/OneShot.exe
) the `.exe` file. _**(OneShot-Setup-x.x.x.exe)**_



##### _Because this app is Free and Open-Source, we cannot afford to sign our code. This means Chrome may warn about an untrusted download, this is normal. Click the arrow icon -> `Keep` to finish downloading. Windows Defender and Mac Gatekeeper will prevent you from running the app the first time._

###### Windows

> Windows protected your PC.

- Click `More Info`
- Click `Run Anyway`


###### _Further instructions for [Windows](https://www.techjunkie.com/windows-protected-your-pc-disable-smartscreen/)

---

## Usage

> ❌ marks the spot...

Click and drag the crosshair to anywhere on any screen.

Double-click the drag icon to center the crosshair on the current display.

To quit in Windows, toggle the app unlocked and right-click > `Close`.

###### On a Mac, the <kbd>Option</kbd> key is used instead of <kbd>Alt</kbd>.

#### Keyboard Shortcuts

Description            | Keys
-----------------------| -----------------------
Toggle the settings window and lock the crosshair in place | <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>X</kbd>
Quickly hide/show the application                          | <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>E</kbd>
Reset all settings and center the window                   | <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>R</kbd>
Display the "About" window details                        | <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>A</kbd>
Move the crosshair a single pixel                          | <kbd>Control</kbd>-<kbd>Alt</kbd>-<kbd>Shift</kbd>-<kbd>Arrows</kbd>


<p align="center">
	<br />
	<img width="120" height="120" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/crosshairs/Actual/ballistic-firedot.png">
	<img width="120" height="120" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/crosshairs/Actual/moa-delta.png">
	<img width="120" height="120" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/crosshairs/Actual/blackout.png">
	<img width="120" height="120" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/crosshairs/Actual/leica-magnus.png">
	<img width="120" height="120" src="https://github.com/5R33CH4/OneShot/raw/master/src/static/crosshairs/Actual/bull-ring-post.png">
</p>

---


## Development

Built with [Electron](https://electronjs.org). Simple HTML and Javascript, no framework.

Start developing in `src/main.js` and `src/renderer.js`.

### Run

```
$ npm install && npm start
```

### Build

_wine_ and _mono_ must be installed for Windows builds (_macOS_)

```
$ npm run build
```


### Publish

```
$ npm run release
```

Then edit the automatically created GitHub Releases draft and publish.


## Bugs

#### Hidden by fullscreen apps

Currently OneShot only works with windowed applications, use `Windowed Fullscreen` mode if your game or application supports it. 

#### Sight is deformed or off by 1 pixel

Due to limitations in chrome we are unable to generate sub-pixel graphics, although there may be a way...



