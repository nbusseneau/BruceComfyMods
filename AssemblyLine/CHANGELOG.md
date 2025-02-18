## Changelog

### 1.1.1

  * Fixed bug where crafting not stopped when inventory closed, sometimes continuing to craft items when next opened.
  * Changed behavior so that `Lshift` + click sets to max if requirements for 10 additional crafts are not met.
  * Added and moved changelog to `CHANGELOG.md`
  * Updated assembly references to `\valheim_Data\managed\` from `\unstripped_corlib\`
  * Updated `README.md` to make +10 and +max crafting options with modifiers more visible.

### 1.1.0

  * Updated for patch 0.217.22. Updated to TMP Text fields
  * Fixed bug where setting max craft amount set count to 0. Count will always be a positive integer.
  * Fixed bug where increment and decrement buttons non-interactable after closing InventoryGUI on upgrade tab and reopening.
  * Fixed bug where crafting continued when InventoryGUI opened after closing without cancelling crafting.

### 1.0.0

  * Initial release.