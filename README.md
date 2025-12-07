# GWToolbox Plugins

This repository contains standalone plugins for GWToolbox++.

## UseRandom Plugin

A plugin that allows using random items from a specified list via the `/userandom` command.

### Usage
```
/userandom <item_id1,item_id2,item_id3,...>
```

Example:
```
/userandom 22,35,46
```

### Building

#### Local Build
1. Clone this repository
2. Run `build-local.bat` - it will automatically clone GWToolboxpp and build the plugin
3. The compiled DLL will be output to the repository root

#### GitHub Actions
- Push to main/master branch to trigger a build
- Use "Run workflow" to create a release with version tagging
- Built artifacts are automatically released

### Installation
1. Download `UseRandomPlugin.dll` from the [Releases](../../releases) page
2. Place it in your GWToolbox `plugins` folder
3. Restart GWToolbox

### PDB Files
The `.pdb` files contain debug symbols and are **not required** for the plugin to work. They're only useful if you need to debug crashes or issues. Most users can ignore them.
