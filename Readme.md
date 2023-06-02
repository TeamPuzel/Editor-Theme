### My simple editor theme, Strawberry 🍓

To install for Xcode, place the files in 

```swift
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

Please note that the non italic light theme is a bit unfinished, since I don't really use it.

The themes marked `(italic)` have more dynamic, italic keywords to make them stand out even more.

There is now a version marked (JB) which uses JetBrains Mono instead of SF

### Features:
- instances of classes are of a slightly warmer green than structs, making them easier to tell apart
- color is used only where neessary, so the theme doesn't look like a 🎄
- the colors work well together and are very pleasing to look at 🍓
- numbers stand out which I found to be more readable

## VSCode

For VSCode the theme isn't really a "theme" rather just a configuration file changing the default one, I'm not willing to bother with their overcomplicated theme system.

The color theme itself is just overriding the colors of the `Visual Studio Dark` theme. There is no light mode.

### VSCode Languages
Because most languages tend to poorly respect the default vscode settings I have manually changed every scope to the correct color for some languages.

Supported languages include:
- Swift (Full)
- Rust (Full)
- Zig (Partial, Zig itself doesn't yet have good enough lsp support for Strawberry to work, so it's missing the green color)
- TypeScript (Full)

## Fleet

There is now a version for Fleet, however it doesn't properly color booleans in Rust for some reason.