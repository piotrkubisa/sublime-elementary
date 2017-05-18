# Theme - Elementary

ElementaryOS inspired UI theme for Sublime Text 2 and Sublime Text 3.

> Project currently is untaintained. If you are interested in maintenance this repository then I'd would happy to transfer ownership of `Theme - Elementary` to you.


## Design

Elementary theme tries to mimic [elementary OS](https://github.com/elementary) user interface.

<!-- Screenshots on gh-pages branch -->

![Dark Variant](http://piotrkubisa.github.io/sublime-elementary/screenshots/dark_autocomplete.png)

![Light Variant](http://piotrkubisa.github.io/sublime-elementary/screenshots/light_variant_search.png)

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

1. Download latest version as [zip-ball](https://github.com/piotrkubisa/sublime-elementary/releases/latest) or click **Download ZIP**, while browsing latest tag (version) on [sublime-elementary](https://github.com/piotrkubisa/sublime-elementary).
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

* Icons

> Since today (19.05.2017) I'd suggest installing [A File Icon package](https://github.com/ihodev/a-file-icon) instead. I have removed all icons, because they were copied from SetiUI project.


* If you set `"elementary_colorful": true` in your user settings you may notice elementarish-blue scrollbars.

![](https://cloud.githubusercontent.com/assets/3073499/7440907/1b351a80-f0cf-11e4-8575-69cab88d300b.png)

Effect:

![](https://cloud.githubusercontent.com/assets/3073499/7440900/f98cbd52-f0ce-11e4-8d9d-a04e76aa3dcd.png)

* `"elementary_light_bottombar": true`

![](https://cloud.githubusercontent.com/assets/3073499/7440902/03168e34-f0cf-11e4-9f59-d055be7883d5.png)

* `"elementary_dark_statusbar": true`

![](https://cloud.githubusercontent.com/assets/3073499/7440903/0d9a2f64-f0cf-11e4-91e4-07c4379ec024.png)

* `elementary_folder_icons` (Light theme with ST2 only)

### Optional

* I suggest set `"overlay_scroll_bars": "enabled"`,
* If you are using light variant I'd also set `"bold_folder_labels": true`
* This theme comes with two Color schemes called `Mustang Bianco` and `Mustang Obsidian` which are modified version of the Mustang.
* Personally, I'd also set `font_face` to `Fira Mono`, `Fira Code` or `Meslo`, because they are very legible. I'd also set: `"line_padding_bottom": 2`, and `"line_padding_top": 2` to add some whitespaces between the lines.
* If you are running Sublime Text on some Linux distro then I'd suggest installing [p-e-w/GTKDarkThemeVariantSetter](https://github.com/p-e-w/GTKDarkThemeVariantSetter) which forces a dark theme of the app window.

## Credits

This project consist some work which haven't been done by me and I am managed to say thanks to [@samuelrafo](https://github.com/samuelrafo/) for designing his light variant of [Elementary Theme](https://github.com/samuelrafo/elementary). In generally speaking I find this repo as fork, trying keep this theme up-to date with latest Sublime Text version showing also his fabulous work done on light variant.
