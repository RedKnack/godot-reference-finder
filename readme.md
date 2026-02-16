# Reference Finder (Godot 4 Editor Plugin)

**Reference Finder** is a lightweight **Godot 4 editor plugin** by **RedKnack Interactive**
that enables searching for Tokens (Functions, Variables, etc) in a whole project by using SHIFT+F12. Singletons included.

- Godot: tested with **4.5.1**
- Language: **GDScript**
- Install path: `addons/reference_finder/`

---

## Features

- Seraching project-wide for Tokens / Variables / Functions (Singletons included)
- No external dependencies

---

## Installation

### Godot Asset Library
1. In Godot: **AssetLib**
2. Search for **Reference Finder**
3. Install
4. Go to **Project → Project Settings → Plugins**
5. Enable **Reference Finder**

### Manual
Copy `addons/reference_finder/` into your project and enable the plugin:
**Project → Project Settings → Plugins**

---

## Usage

1. Enable the plugin.
2. Select a Token / Variable / Function
3. Press Shift + F12
4. Review output in the References tab.
5. Doubleclick on results to open the respective file

To adapt behavior or make changes, check:
- `addons/reference_finder/plugin.gd`
- `addons/reference_finder/references_panel.gd`

---

## License

### Plugin code
MIT License — see `LICENSE`.

### Third-party assets:
NONE


