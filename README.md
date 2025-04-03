# Browse without distractions

![Static Badge](https://img.shields.io/badge/Firefox-%E2%9C%95-red)
![Static Badge](https://img.shields.io/badge/Cachy_Browser-%E2%9C%95-red)
![Static Badge](https://img.shields.io/badge/Firefox_ESR_128.8-✓-blue)
![Static Badge](https://img.shields.io/badge/Firefox_Developer_Edition-%E2%9C%95-red)

Tabs make less noise, giving more room to browse the web letting you see what’s important to prevent you from getting distracted. One file without surprises, as simple as you always wanted.

## Look and feel

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gabrielcapilla/min/refs/heads/main/assets/images/lookandfeel.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gabrielcapilla/min/refs/heads/main/assets/images/headerlight.png">
</picture>

## :dart: Keyboard Centered Design

Jump to any site quickly. Use the shortcuts.

- `Ctrl + W` Closes a Tab
- `Ctrl + T` Opens a New Tab
- `Ctrl + L` Focuses the URL bar
- `Ctrl + B` Shows you the Bookmarks
- `Ctrl + H` Shows you the History Bar
- `Ctrl + R` Refresh the page you're on
- `Ctrl + Alt + R` Clutter-free Reader View
- `Ctrl + Shift + B` Hide/unhide Bookmarks bar
- `Ctrl + Shift + A` Quick open for Add-Ons
- `Ctrl + Shift + T` Re-opens a tab that you just closed
- `Alt + Left Arrow` Go Back
- `Alt + Right Arrow` Go Forward

## :ninja: Protect Your Privacy

Works on top of Firefox, and [uBlock Origin works best on Firefox](https://github.com/gorhill/uBlock/wiki/uBlock-Origin-works-best-on-Firefox). Stops ads and trackers, so you can browse faster without being tracked. And when you’re using a slow or expensive internet connection, it lets you block scripts and images, so pages load faster and use less data.

## :gear: How To Install

To install this theme, do the following:

- Type `about:config` in the address bar of Firefox.
- Put it on `true`

  ```md
  toolkit.legacyUserProfileCustomizations.stylesheets
  ```

Chrome folder:

- Type `about:profiles` in the address bar of Firefox and find your profile folder.
- Create a folder named `chrome` in your profile folder(s). Add the file `userChrome.css` in the `chrome` folder. Then restart the browser.

## :people_hugging: Make It Yours

### Recommended Add-ons

- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
- [Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/)

### Do you use KDE?

Look your `about:config` the following parameters and change the value to `1`

```md
widget.use-xdg-desktop-portal.file-picker
```

```md
widget.use-xdg-desktop-portal.mime-handler
```

### Rounded corners

In `about:config` you can make the bottom window corners rounded by setting to `true`.

```md
widget.gtk.rounded-bottom-corners.enabled
```

## Miscellaneous

### Inspiration

Inspired by [Min Browser](https://github.com/minbrowser/min). I wanted to bring the Min Browser experience closer to Firefox. Min is written entirely with CSS and JavaScript using Electron, and is open-source software.
