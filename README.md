# How to Install

## First of all...

## Setting up directories

```
mkdir -p .config/yabai && mkdir -p .config/skhd; touch .config/yabai/yabairc && touch .config/skhd/skhdrc
```

## Installing 

Ensure that brew is up to date and then install yabai.:

```
brew update && brew upgrade && brew clanup; brew install koekeishiya/formulae/yabai
```

Tap it, so brew can update it in post system updates:

```
brew tap koekeishiya/formulae/yabai
```

Then, just launch the services with launchctl or simply with brew service command,

```
brew services start yabai && brew services enable yabai
```

Also, remember to create the default structure so yabai can work properly on background.