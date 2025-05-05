<h1 align="center"><strong>Neptune Firefox Windows</strong></h1>

**Instructions:** 
- This theme is compatible with the latest release of Firefox.
- To enable adaptive colors, you need to install the **[Adaptive Tab Bar Color](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour)** extension. 

<img src="info/preview.png" alt="Preview Image" width="800px">

## Installation

- Download the theme file and unzip the `chrome` folder into your `profile` folder.
- You can modify the background in the `userContent.css`, for the light and dark modes

```css
body {
		background: url("neptune/image/Abstract_Dreamscapes_Light.png") center/cover fixed !important;

		@media (prefers-color-scheme: dark) {
			background: linear-gradient(180deg,
                #000000 0%,
                #120024 40%,
                #1a013b 75%,
                #1a013c 100% 
               ) fixed !important;
  			}
}
```

## Configuration

- **about:config**
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
    - Set `svg.context-properties.content.enabled` to `true`.
    - Set `widget.non-native-theme.use-theme-accent` to `true`.

- **Required settings**
    - In a horizontal layout, a flexible spacer (Customize Toolbar) must be placed on both sides of the address bar (very important). If more flexible spacers are being used, the excess ones must be removed.

ENJOY!
