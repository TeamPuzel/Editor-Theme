### My simple editor theme, Strawberry 🍓

To install for Xcode, place the files in 

```swift
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

Please note that the light theme is a bit unfinished, since I don't really use it.

### Features:
- instances of classes are a slightly warmer green than structs, making it easier to tell them apart :)
- color is used only where neessary, so the theme doesn't look like a 🎄
- the colors work well together and are very pleasing to look at 🍓😋
- numbers stand out a bit more
- looks pretty with Night Shift on 🌙

<img width="1280" alt="Screenshot 2022-11-11 at 14 20 24" src="https://user-images.githubusercontent.com/94306330/201350347-fdf5229d-4d6f-4244-9887-d3263c9daf3c.png">

## VScode

For VSCode, the theme isn't really a "theme" rather a configuration file, `settings.json` since that editor has pretty bad settings out of the box. It also overrides some ugly 🎄 settings rust-analyzer forces on, like underlining variables, and replaces the font with San Francisco mono (if you have it installed, if not Apple has a download link on their site, you can also use your favorite font, or just the default if you're not on macOS 😉).

The color theme itself is just overriding the colors of the `Visual Studio Dark` theme. There is no light mode.

## Other editors

There is currently no support for other editors, but it's easy enough to just create one based on the hex values from the VScode version.
