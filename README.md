# Helix Editor Configuration

My personal Helix editor configuration with seoul256-dark-hard theme and custom keybindings.

## Quick Setup

## Destructive One-liner Setup

```bash
rm -rf ~/.config/helix && git clone https://github.com/justingosan/helix.git ~/.config/helix
```

Clone and overwrite existing config:

```bash
# Backup existing config (optional)
mv ~/.config/helix ~/.config/helix.backup

# Clone this repo
git clone https://github.com/justingosan/helix.git ~/.config/helix
```

Or if you already have a helix config and want to overwrite:

```bash
# Remove existing config
rm -rf ~/.config/helix

# Clone this repo
git clone https://github.com/justingosan/helix.git ~/.config/helix
```

## Features

- **Theme**: seoul256-dark-hard
- **Line numbers**: Relative
- **Mouse**: Enabled
- **Auto-completion**: Enabled
- **Rulers**: 80 and 120 columns
- **Whitespace rendering**: Spaces and tabs visible

## Key Bindings

### Normal Mode
- `Ctrl-s`: Save
- `Ctrl-q`: Quit
- `Ctrl-a`: Select all
- `Ctrl-x`: Cut line
- `Ctrl-p`: File picker
- `Ctrl-f`: Search forward
- `Ctrl-r`: Search backward
- `Space-w`: Save
- `Space-q`: Quit
- `Space-x`: Save and quit
- `Space-f`: File picker
- `Space-b`: Buffer picker
- `Space-g`: Go to definition
- `Space-r`: Rename symbol
- `Space-c`: Toggle comments

### Insert Mode
- `Ctrl-s`: Save
- `Ctrl-space`: Trigger completion
- `Ctrl-n`: Trigger completion
- `Ctrl-p`: Show signature help

## Installation

Make sure you have Helix installed:

```bash
# macOS
brew install helix

# Or build from source
git clone https://github.com/helix-editor/helix
cd helix
cargo install --path helix-term
```
