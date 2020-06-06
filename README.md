# CoffeeCupCursorTheme
A cursor theme for those who need a daily dose of caffeine.

## Preview:
<img src="DarkPreview.png">

## Installation

You can find the cursors on the releases page for Mac (via a [Mousecape](https://github.com/alexzielenski/Mousecape) .cape), Linux, and Windows:

[https://github.com/isaacrobinson2000/CoffeeCupCursorTheme/releases](https://github.com/isaacrobinson2000/CoffeeCupCursorTheme/releases)

#### Linux

Download and extract the theme from the tar.gz file, and then place the theme in "/usr/share/icons" or "~/.icons"

#### Mac

Download the the .cape file, and then double click on it. You will need to install [Mousecape](https://github.com/alexzielenski/Mousecape/releases) first.

#### Windows

Download and extract the theme from the zip file, then right click on the "install.inf" file and click "Install".

## Building From Source

This project uses the CursorCreate build system for building cursors. You can find installation directions at the link below:

[https://github.com/isaacrobinson2000/CursorCreate](https://github.com/isaacrobinson2000/CursorCreate)

Once you have installed CursorCreate (PyPI install recommended), you can build the theme by following the commands below:
```bash
git clone https://github.com/isaacrobinson2000/CoffeeCupCursorTheme.git
cd CoffeeCupCursorTheme
# If you used a prepackaged binary you will need to write the full path to the binary instead of just 'CursorCreate':
CursorCreate --build build.json
```
The built themes for Mac, Windows, and Linux should show up in sub-directories called 'mousecape_macos', 'windows', and 'linux'.
