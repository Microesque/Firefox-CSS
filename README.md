# Firefox-CSS - Microesque
Custom Firefox CSS I made for myself. Feel free to use or modify it ¯\\_(ツ)_/¯

Currently under update. Download/clone the [pre-refactor](https://github.com/Microesque/Firefox-CSS/releases/tag/pre-refactor) release to get the results below.

**`Preview:`**
<div style="text-align: left;">
<img src="https://raw.githubusercontent.com/wiki/Microesque/Firefox-CSS/images/Preview1.png" alt="img">
</div>

>- `Bookmarks toolbar` is displayed as a sidebar on the left. **Left-click** or **middle-mouse-click** to use the elements. If the list is too long, use the mouse wheel to scroll. **Ctrl+Shift+B** toggles it by default.
>- The `X` buttons that close the tabs are removed. Use **middle-mouse-click** instead.
>- Remodeled `NewTab` shortcuts and the ability to add custom background image.
>- Remodeled `about:` tabs.
>- Most UI elements are modified to be a lot smaller.
>- ...

---

### Setup
  - Follow the [How to enable custom CSS for Firefox?](#how-to-enable-custom-css-for-firefox)
  - Make sure to use `horizontal tabs` and not `vertical tabs`.
  - Use the `default light theme`.
  - **Right-click** anywhere on the UI and click `Customize Toolbar`. Place the `Bookmarks toolbar items` element into the left toolbar by dragging.

<div style="text-align: left;">
<img src="https://raw.githubusercontent.com/wiki/Microesque/Firefox-CSS/images/ToolbarCustomizations.png" alt="img" width="750px">
</div>

  - Open `FireFox settings` and navigate to `Home`. Change your settings to match the image below.
  
<div style="text-align: left;">
<img src="https://raw.githubusercontent.com/wiki/Microesque/Firefox-CSS/images/NewtabSettings.png" alt="img" width="750px">
</div>

---

### How to enable custom CSS for Firefox?
  - Navigate to `about:config`.
  - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
  - Set the value to `true`.
  - Navigate to `about:profiles`.
  - Find the profile that is in use, and click `Open Folder` on its `Root Directory`.
  - Create a folder named `chrome`.
  - Copy the repository files into the `chrome` folder.
  - Restart Firefox.

---

### How to make basic modifications?
  - I put basic settings like color, size, and similar values that I thought I might want to change in the future into the `variables.css` file. You can modify them from there.

---

### Notes
  - This is a personal project, so it isn't tested thoroughly.
  - Only made for Windows. I don't know how it looks like on other OS.
