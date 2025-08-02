## AeroSpace: i3-like Tiling Window Manager for macOS

AeroSpace is a powerful, keyboard-centric tiling window manager for macOS, inspired by [i3](https://i3wm.org/). It brings fast workspace switching, advanced window management, and a highly customizable configuration to macOS users—without requiring you to disable System Integrity Protection (SIP).

### Why Use AeroSpace?

- **Productivity**: Manage windows efficiently with keyboard shortcuts and tiling layouts.
- **Workspaces**: AeroSpace emulates virtual workspaces, overcoming limitations of native macOS Spaces ([details](https://nikitabobko.github.io/AeroSpace/guide#emulation-of-virtual-workspaces)).
- **Multi-monitor support**: Assign workspaces to specific monitors ([multi-monitor guide](https://nikitabobko.github.io/AeroSpace/guide#multiple-monitors)).
- **Plain text config**: Easily edit your setup in a TOML file ([default config](https://nikitabobko.github.io/AeroSpace/config-examples/default-config.toml)).
- **CLI-first**: Control everything from the command line, with manpages and shell completion.
- **No SIP required**: Safe to use on modern macOS systems.

### Documentation & Resources

- [AeroSpace Guide](https://nikitabobko.github.io/AeroSpace/guide)
- [AeroSpace Commands](https://nikitabobko.github.io/AeroSpace/commands)
- [AeroSpace Goodies](https://nikitabobko.github.io/AeroSpace/goodies)
- [GitHub Repository](https://github.com/nikitabobko/AeroSpace)

### Key Features

- Tree-based tiling model ([tree paradigm](https://nikitabobko.github.io/AeroSpace/guide#tree))
- Fast workspace switching (no animations)
- Customizable keyboard shortcuts and binding modes
- Floating and tiling layouts, accordion layouts
- Extensive callback and automation support

---

## Keyboard Shortcuts (from `aerospace.toml`)

### Main Mode

- `alt-slash`: Layout tiles horizontal vertical
- `alt-comma`: Layout accordion horizontal vertical
- `alt-h`: Focus left
- `alt-j`: Focus down
- `alt-k`: Focus up
- `alt-l`: Focus right
- `alt-shift-h`: Move left
- `alt-shift-j`: Move down
- `alt-shift-k`: Move up
- `alt-shift-l`: Move right
- `alt-minus`: Resize smart -100
- `alt-equal`: Resize smart +100
- `alt-1` to `alt-9`: Switch to workspace 1-9
- `alt-d`: Switch to workspace D (Desktop)
- `alt-right`: Workspace next (wrap-around)
- `alt-left`: Workspace prev (wrap-around)
- `alt-shift-1` to `alt-shift-9`: Move node to workspace 1-9
- `alt-shift-d`: Move node to workspace D
- `alt-f`: Toggle fullscreen
- `alt-shift-s`: Screenshot to clipboard
- `alt-tab`: Workspace back and forth
- `alt-shift-tab`: Move workspace to monitor (wrap-around next)
- `alt-shift-semicolon`: Switch to service mode
- `alt-shift-space`: Switch to apps mode

### Service Mode

- `esc`: Reload config, return to main mode
- `r`: Flatten workspace tree, return to main mode
- `f`: Toggle floating/tiling layout, return to main mode
- `backspace`: Close all windows but current, return to main mode
- `alt-shift-h`: Join with left, return to main mode
- `alt-shift-j`: Join with down, return to main mode
- `alt-shift-k`: Join with up, return to main mode
- `alt-shift-l`: Join with right, return to main mode
- `down`: Volume down
- `up`: Volume up
- `shift-down`: Set volume to 0, return to main mode

### Apps Mode

- `t`: Open iTerm
- `s`: Open System Settings
- `l`: Open Slack
- `p`: Open Postman
- `w`: Open WhatsApp
- `f`: Open Finder
- `n`: Open Notes
- `g`: Open Google Chrome
- `c`: Open Visual Studio Code
- `m`: Open Spotify

---

## Window Automation (on-window-detected)

- Finder, System Settings: Float and move to workspace D
- Chrome: Move to workspace 1
- VSCode: Move to workspace 2
- iTerm2, Terminal, Warp: Move to workspace 3
- Postman, Notes: Move to workspace 4
- Slack, WhatsApp: Move to workspace 5

---

## Getting Started

- [Installation Guide](https://nikitabobko.github.io/AeroSpace/guide#installation)
- [Configuration Guide](https://nikitabobko.github.io/AeroSpace/guide#configuring-aerospace)
- [Commands Reference](https://nikitabobko.github.io/AeroSpace/commands)

For more details, visit the [AeroSpace GitHub repo](https://github.com/nikitabobko/AeroSpace) and join the [community discussions](https://github.com/nikitabobko/AeroSpace/discussions).

---

## Extensions

### SwipeAeroSpace

A nice extension to be able to move between workspaces with the mouse gestures

- [Guide](https://github.com/acsandmann/aerospace-swipe)

### Raycast

A better solution for the mac `Spotlight` that enhances the things you can do and also can be expandable with extension for other applications
