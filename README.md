# muzak

## Setup

```
# In one terminal:
> sclang
# ...
SuperDirt.start

# In another terminal
# Execute Atom via Stack to set env vars correctly for Tidal
cd ~/git/muzak && stack exec atom .
```

## Installation

### macOS

```bash
brew cask install supercollider
stack build
```

### Arch Linux

Using [pikaur] as our [pacman] wrapper:

```bash
# Install pre-reqs
pikaur -S supercollider atom-editor-bin
# Install TidalCycles plugin for Atom
apm install tidalcycles
# Build TidalCycles
stack build
```

[pikaur]: https://github.com/actionless/pikaur
[pacman]: https://wiki.archlinux.org/index.php/Pacman 
