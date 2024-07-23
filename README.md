# Chezmoi Config

## Init New Machine (MacOS)

```
#!/bin/bash

# Install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
eval "$(/opt/homebrew/bin/brew shellenv)"

# Install and initialize chezmoi
brew install chezmoi
chezmoi init https://github.com/mannkind/chezmoi-config.git
```
