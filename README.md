# homebrew-herds-cli

Homebrew tap for the [Herds CLI](https://github.com/herds-social/herds-cli).

## Install

```bash
brew tap herds-social/herds-cli
brew trust --formula herds-social/herds-cli/herds   # required on Homebrew 6.0.0+ (5.2.0+)
brew install herds
```

## Upgrade

After a new CLI release updates the formula in this tap:

```bash
brew update && brew upgrade herds
```

## Releases

CLI versions are tagged in the main repo as `cli-vX.Y.Z` (for example `cli-v4.2.1`). Each tag triggers a GitHub Release with source and wheel assets. This tap's `Formula/herds.rb` pins the release sdist URL and SHA256.

See [herds-cli releases](https://github.com/herds-social/herds-cli/releases) for changelog and assets.
