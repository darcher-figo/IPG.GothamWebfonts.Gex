# Gex Gotham Font

> Cloned from icon repo, will be updated shortly


This repository contains icons[^1.1] intended for use in the Gex Component
Library[^1.2] per the Gex Design System[^1.3] housed in the GexUI[^1]
repository.

[^1.1]: <https://figma.com/file/kvMmlPoqMjNLraXH650Vcz/ℹ️-Gex-Icons>
[^1.2]: <https://figma.com/file/TzBgRzUiUB7CBAoJU2LEy9/🧩-Gex-Components>
[^1.3]: <https://figma.com/file/9ps3lRhg6kKFkKnQYeuTab/🎨-Gex-Styles>
[^1]: <https://github.com/PetPartners/IPG.DesignSystems.Gex>

## Setup

The npm dependencies are light as you can see in [package.json](./package.json).
Lets hop in and get you some Icon's!

### Getting started

```shell
# clone repository locally...
gh repo clone darcher-figo/GexGothamFont && cd GexGothamFont

# align node version
nvm use                 # ...or nvm install
nvm install-latest-npm  # ...or npm i -g npm@latest

# check versions
node  --version         # e.g. 21.6.1
npm   --version         # e.g. 10.4.0

# setup env
npm run setupUI         # there's no UI yet... but checkout `./src` for icons.

# then...
npm run build           # look in `./dist` for full optimized icons bundle.
```

