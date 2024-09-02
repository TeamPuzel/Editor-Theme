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

# Screenshots

### Xcode
<img width="1440" alt="image" src="https://github.com/TeamPuzel/Editor-Theme/assets/94306330/690ee9d7-c910-43f0-8a05-b7ef96a2aaa7">
<img width="1440" alt="image" src="https://github.com/TeamPuzel/Editor-Theme/assets/94306330/4ae6bd4b-780d-472e-a235-2b53331b71a7">

### VSCode
<img width="1440" alt="image" src="https://github.com/TeamPuzel/Editor-Theme/assets/94306330/85f322ad-d355-4011-bcf8-31f9936df841">

### Zed
<img width="1840" alt="image" src="https://github.com/TeamPuzel/Editor-Theme/assets/94306330/8b8bf44c-f093-406b-b74c-4cb806ed8ebb">

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
