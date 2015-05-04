# Theme - Elementary

ElementaryOS inspired UI theme for Sublime Text 2 and Sublime Text 3.

Project currently is in development stage. You can check progress [here](https://github.com/piqus/sublime-elementary/issues/1).

## Design

Elementary theme tries to mimic [elementary OS](https://github.com/elementary) user interface.

<!-- Screenshots needed on gh-pages branch -->

## Installation

### Sublime Package Control

If you are using excellent [Sublime Package Control](https://packagecontrol.io) you can simply install Elementary Theme via `Package Control: Install Package` menu item (`Ctrl+Shift+P` or `Cmd+Shift+P` on OS X), where this theme is listed as:

```
Theme - Elementary
```

### Git

Simply clone this repository to your Sublime Packages/ folder (available via  `Preferences -> Browse Packages...`). While inside the Packages/ directory, clone the theme repository using the command below:

```bash
git clone https://github.com/piqus/sublime-elementary.git "Theme - Elementary"
```

### Manual installation

1. Download latest version as [zip-ball](https://github.com/piqus/sublime-elementary/archive/0.2.0.zip) or click **Download ZIP**, while browsing latest tag (version) on [sublime-elementary](https://github.com/piqus/sublime-elementary).
2. As it was aforementioned in Git installation method, you need to **locate** Sublime Text Packages/ directory.
3. **Unzip** the files and **rename** the folder to **Theme - Elementary**.
4. **Copy** the folder into your Sublime Text Packages/ directory

## Activation

After package installation you will need to set `theme` user setting in `Preferences -> Settings - User` or look for `Preferences: Settings - User` via Goto-Anything.

### Dark variant

Dark variant of theme is only compatible with Sublime Text 3 version by now. Set theme configuration as it is shown below:

* Sublime Text 3:

```json
{
  "theme": "Elementary Dark.sublime-theme"
}
```

### Light variant

Light theme is also compatible with Sublime Text 2, depending on version use proper theme:

* Sublime Text 3:

```json
{
  "theme": "Elementary Light 3.sublime-theme"
}
```

* Sublime Text 2:

```json
{
  "theme": "Elementary Light.sublime-theme"
}
```

## Configuration

Elementary themes comes with various setings which can be set using `Preferences -> Settings - User` file.

## Features

<!-- Screenshots and description needed -->

* `elementary_light_bottombar`
* `elementary_dark_statusbar`
* `elementary_light_bottombar`
* `elementary_folder_icons` (Light theme with ST2 only)

### Optional

* `"overlay_scroll_bars": "enabled"`
* `"bold_folder_labels": true`
* Color schemes:
	* Ocean Next.
	* Mustang Bianco.
	* Mustang Obsidian.
	* Monokai Extended.

## Contribution &amp; suggestions

If you see something looking *just bad*, please let me know using [issues](https://github.com/piqus/sublime-elementary/issues/). Of course, any pull-requests are greatly welcome, feel free to commit changes!

## Credits

This project consist some work which haven't been done by me and I am managed to say thanks to [@samuelrafo](https://github.com/samuelrafo/) for designing his light variant of Elementary Theme published in his repository [samuelrafo/elementary](https://github.com/samuelrafo/elementary). In generally speaking I find this repo as fork, trying keep this theme up-to date with latest Sublime Text version showing also his fabulous work done on light variant.
