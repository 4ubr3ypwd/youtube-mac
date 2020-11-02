# YouTube

![](screenshot.png)

An (unofficial) native MacOS App for YouTube.com.

# Install

## Homebrew Cask

### Install

```bash
brew tap aubreypwd/homebrew-cask
brew update
brew cask install youtube
```

### Upgrade

```bash
brew update
brew upgrade youtube
```

## Download

Or download the `.dmg` in [releases](https://github.com/aubreypwd/youtube-mac/releases/latest) and install per usual.

*_Note, you will have to Right-click on the YouTube app to run for the first time, even after upgrading._*

# Development

1. Clone repo
2. `npm install`
3. `npm run build`

`npm run build` will built the application to `build/` and  `npm run dist` to generate a `.dmg` in `dist/` for distribution and installation.
