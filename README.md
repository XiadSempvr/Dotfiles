# How to Install

## First of all...

## Setting up directories

```
mkdir -p .config/yabai && .config/skhd; touch .config/yabai/yabairc .config/skhd/skhdrc
```

## Installing 

Once you've setted the directory structure, ensure that brew is up to date and then install yabai:

```
brew update && brew upgrade && brew cleanup; brew install koekeishiya/formulae/yabai
```

Tap it, so brew can update it in post system updates:

```
brew tap koekeishiya/formulae/yabai
```

Then, just launch the services with launchctl or simply with brew service command:

```
brew services start yabai && brew services enable yabai
```

Also, remember to create the default structure so yabai can work properly on background.
