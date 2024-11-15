# Firefox Laconic | Browse without distractions  

<!-- CSS -->
<style>
:root {
  --font-size: 10px;
}

.frame {
  margin: 0 auto;
  gap: 4px;
  width: 50%;
  height: 4vh;
  display: flex;
  align-items: center;
  justify-content: right;
  background-color: rgb(4, 30, 73, 0.5);
  border-radius: 4px;
}

.frame::before {
  color: #fff;
  content: "Compatible";
  font-weight: bold;
  margin-right: auto;
  margin-left: 14px;
}

.container {
  width: 64px;
  height: 32px;
  margin-left: -16px;
  margin-right: 8px;
  position: relative;
  border-radius: 18px;
  background-color: #020d20;
}

.true, .false {
  top: 50%;
  left: 60%;
  width: 1em;
  height: 1em;
  display: flex;
  border-radius: 50%;
  position: absolute;
  align-items: center;
  justify-content: center;
  transform: translate(-50%, -50%);
}

.true {
  border: 2px solid #1970e3;
}

.false {
  border: 2px solid #e18022;
}

.true::before {
  content: "✓";
  color: #1970e3;
  font-size: var(--font-size);
}

.false::before {
  content: "✕";
  color: #e18022;
  font-size: var(--font-size);
}

.firefox-icon, .cachy-icon, .firefox-dev-icon {
  top: 50%;
  left: 38%;
  width: 64%;
  height: 64%;
  position: absolute;
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
  transform: translate(-50%, -50%);
}

.firefox-icon {
  background-image: url("assets/icon/firefox-icon.png");
}

.cachy-icon {
  background-image: url("assets/icon/cachy-icon.png");
}

.firefox-dev-icon {
  background-image: url("assets/icon/firefox-dev-icon.png");
}
</style>

<div class="frame">
<!-- Item 1 -->
  <div class="container">
    <div class="false">
    </div>
    <div class="firefox-dev-icon"></div>
  </div>

<!-- Item 2 -->
  <div class="container">
    <div class="true">
    </div>
    <div class="cachy-icon"></div>
  </div>

<!-- Item 3 -->
  <div class="container">
    <div class="true">
    </div>
    <div class="firefox-icon"></div>
  </div>
</div>

<!-- END CSS -->

Tabs in Laconic make less noise, giving more room to browse the web letting you see what’s important to prevent you from getting distracted. One file without surprises, as simple as you always wanted.

<!-- ![image](/assets/images/headerlight.png) -->
![image](/assets/images/headerdark.png)

## :dart: Keyboard Centered Design

See quick definitions and answers. Jump to any site quickly. Use the shortcuts.

- `Ctrl + W` Closes a Tab
- `Ctrl + T` Opens a New Tab
- `Ctrl + L` focuses the URL bar
- `Ctrl + B` shows you the Bookmarks
- `Ctrl + H` shows you the History Bar
- `Ctrl + R` Refresh the page you're on
- `Ctrl + Alt + R` Clutter-free Reader View
- `Ctrl + Shift + A` Quick open for Add-Ons
- `Ctrl + Shift + T` Re-opens a tab that you just closed
- `Alt + Left Arrow` Go Back
- `Alt + Right Arrow` Go Forward

## :ninja: Protect Your Privacy

Works on top of Firefox, and [uBlock Origin works best on Firefox](https://github.com/gorhill/uBlock/wiki/uBlock-Origin-works-best-on-Firefox). Stops ads and trackers, so you can browse faster without being tracked. And when you’re using a slow or expensive internet connection, it lets you block scripts and images, so pages load faster and use less data.

## :gear: How To Install

To install this theme, do the following:

- Type `about:config` in the address bar of Firefox.
- Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and put it on `true`. Then restart the browser.

Chrome folder:

- Type `about:profiles` in the address bar of Firefox and find your profile folder.
- Create a folder named `chrome` in your profile folder(s). Add the file `userChrome.css` in the `chrome` folder.

## :people_hugging: Make It Yours

### Do you use KDE?

Add  your `about:config` the following parameters:

- `widget.use-xdg-desktop-portal.file-picker` change the value to `1`
- `widget.use-xdg-desktop-portal.mime-handler` change the value to `1`

### Rounded corners

In `about:config` you can make the bottom window corners rounded by setting `widget.gtk.rounded-bottom-corners.enabled` to `true`.

## Miscellaneous

### Recommended Add-ons

- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
- [Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/)

### Inspiration

Inspired by [Min Browser](https://github.com/minbrowser/min). I wanted to bring the Min Browser experience closer to Firefox. Min is written entirely with CSS and JavaScript using Electron, and is open-source software.
