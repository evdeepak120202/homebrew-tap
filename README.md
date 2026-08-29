# Homebrew tap — evdeepak120202

Formulae for my macOS apps.

```bash
brew install evdeepak120202/tap/tidewell
```

## Tidewell

A file organiser for macOS that cannot delete your files. Watches folders, files what
lands in them, previews before it acts, and undoes any run.

Source and issues: <https://github.com/evdeepak120202/tidewell>

### Why a formula and not a cask

A cask downloads a prebuilt app, which macOS quarantines. Tidewell is not notarised —
notarisation needs a paid Apple Developer membership the project does not have — so a
quarantined download would refuse to open without a trip to System Settings.

This formula compiles on your own machine instead. Nothing is downloaded as an executable,
so nothing is quarantined, and the install is cleaner than most notarised apps. It needs
the Xcode command line tools, which Homebrew resolves for you.
