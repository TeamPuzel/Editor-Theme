### My simple editor theme, Strawberry 🍓

To install for Xcode, place the files in 

```swift
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

Please note that the non italic light theme is a bit unfinished, since I don't really use it.

The themes marked `(italic)` have more dynamic, italic keywords to make them stand out even more.

### Features:
- instances of classes are of a slightly warmer green than structs, making them easier to tell apart :)
- color is used only where neessary, so the theme doesn't look like a 🎄
- the colors work well together and are very pleasing to look at 🍓😋
- numbers stand out a bit more
- keywords are of a very satisfying strawberry color, as they are the most important and describe the flow of code
- looks pretty with Night Shift on 🌙

<img width="400" alt="image1" src="https://user-images.githubusercontent.com/94306330/201350347-fdf5229d-4d6f-4244-9887-d3263c9daf3c.png">

italic:

<img width="400" alt="image2" src="https://user-images.githubusercontent.com/94306330/202185178-f3bdf765-e918-445a-bc88-f6bcb8e46cb2.png">

<img width="400" alt="image3" src="https://user-images.githubusercontent.com/94306330/202185584-d6bb1fcd-d8e6-4e2a-823e-d86d142bb9d5.png">


## VScode

For VSCode, the theme isn't really a "theme" rather a configuration file, `settings.json` since that editor has pretty bad settings out of the box. It also overrides some ugly 🎄 settings rust-analyzer forces on, like underlining variables, and replaces the font with San Francisco mono (if you have it installed, if not Apple has a download link on their site, you can also use your favorite font, or just the default if you're not on macOS 😉).

Telemetry is also disabled 🕵🏻

The color theme itself is just overriding the colors of the `Visual Studio Dark` theme. There is no light mode.

## Other editors

There is currently no support for other editors, but it's easy enough to just create one based on the hex values from the VScode version.
