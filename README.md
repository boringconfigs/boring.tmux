# boring.tmux

A tmux configuration with a focus on simplicity and usability.

## Features

- **Prefix:** `C-Space`
- **Mouse support:** Enabled.
- **Clipboard:** Yanking in tmux copies to the system clipboard.
- **Window management:**
  - Windows are automatically renamed.
  - Window and pane indexing starts from 1.
  - `Prefix-0` to `Prefix-9` switch to or create a window at that index.
- **Styling:**
  - Catppuccin theme (macchiato flavor).
  - Custom status bar, panes, and window styling.
- **Vim mode:** Vim key bindings are enabled in copy mode.
- **Reload:** `Prefix-r` reloads the tmux configuration.

## Configuration

The main configuration file is located at `.config/tmux/tmux.conf`.

### Prefix

The default tmux prefix `C-b` is replaced with `C-Space`.

### Key bindings

- `Prefix-r`: Reloads the tmux configuration.
- `Prefix-0` to `Prefix-9`: Switch to or create a window at the specified index.

### Theming

This configuration uses a lightweight, custom Catppuccin theme. The default flavor is "macchiato", but it can be changed by modifying the `@catppuccin_flavor` variable in `.config/tmux/tmux.conf`.
## Installation

You can find installation instructions from [here](https://github.com/boringconfigs/#installation).
