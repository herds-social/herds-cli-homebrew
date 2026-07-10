# herds-cli-homebrew

Homebrew tap for the [Herds CLI](https://github.com/herds-social/herds-cli).

## Install

```bash
brew tap herds-social/herds-cli-homebrew https://github.com/herds-social/herds-cli-homebrew.git
brew trust herds-social/herds-cli-homebrew   # first install on Homebrew 4.x+
brew install herds
```

The repo is not named `homebrew-herds-cli-homebrew`, so the explicit GitHub URL is required for `brew tap`.

## Upgrade

After a new CLI release updates the formula in this tap:

```bash
brew update && brew upgrade herds
```

## Releases

CLI versions are tagged in the main repo as `cli-vX.Y.Z` (for example `cli-v4.2.1`). Each tag triggers a GitHub Release with source and wheel assets. This tap's `Formula/herds.rb` pins the release sdist URL and SHA256.

See [herds-cli releases](https://github.com/herds-social/herds-cli/releases) for changelog and assets.
