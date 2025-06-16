# 🪟 dwm - dynamic window manager

> **Custom build for Void Linux** - A highly customized, minimal, and lightning-fast window manager

## 📸 Screenshots
![dwm Screenshot](screenshots/desktop.png)
*Main desktop with tiling layout*

![dwm Bar](screenshots/statusbar.png)
*Custom status bar with system information*

## 🎨 Key Changes

- **Modkey**: Set to `Hyper` key (Mod4Mask) instead of `Alt`
- **Hyper key workflow** - Uses `Hyper` key as primary modifier
- **System status integration** - Real-time system detailed information display
- **Bottom bar placement** - Status bar positioned at bottom of screen
- **Enhanced patches applied**:
  - `noborder` - Removes borders when single window
  - `fakefullscreen` - Proper fullscreen handling useful for game testing :)
  - `blanktags` - Hides tag numbers, also customized its behavior to show tag number when no window
- **dmenu** - Case-insensitive search, bottom placement, activation by middle-click on status bar
- **Color scheme**: mystic violet theme
- **Font**: Fixed 12pt font
- **Tags**: Reduced to 5 tags (1-5) for clearance 
- **Border**: Minimal border styling
- **Snap**: Reduced snap pixels for smoother window management

## 🎯 Status Bar

The status bar displays:
- Current time
- System RAM usage
- System CPU load

## ⌨️ Keybindings

### Window Management
| Key | Action |
|-----|--------|
| `Hyper + q` | Kill focused window |
| `Hyper + s/d` | Change focus |
| `Hyper + z` | Make focused window master |
| `Hyper + f` | Toggle window float |
| `Hyper + w` | Toggle status bar |
| `Hyper + a` | Launch dmenu |

### Layout Control
| Key | Action |
|-----|--------|
| `Hyper + Shift + r` | Tiling layout |
| `Hyper + Shift + f` | Floating layout |
| `Hyper + Shift + v` | Monocle layout |
| `Hyper + x/c` | Resize master area |
| `Hyper + Shift + x/c` | Change master count |

### Mouse Actions
| Action | Result |
|--------|--------|
| Middle-click status bar | Launch dmenu |
| Middle-click window title | Kill window |
| Left-click layout symbol | Enable tiling |
