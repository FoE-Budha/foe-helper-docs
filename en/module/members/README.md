---
description: Displays complete guild member information, including GBs, treasury stock, guild buildings, and participation stats.
---

# Guild Member Overview

![Icon](./.images/icon.png)

The Guild Member Overview module displays detailed information about your guildmates, including their Great Buildings, guild buildings, treasury resources, collection potential per day, and their current era.

## Menu Overview

![Structure](./.images/menu-structure.png)

The interface includes:

- **Title Bar** with [Configuration](#configuration) menu
- A **search bar** (can be toggled in [Configuration](#configuration))
- [**Tabs**](#tabs) for switching between views
- A **content area** displaying tab-specific data
- **Last updated timestamp** in bottom right corner

## Configuration

![Configuration](./.images/config-menu.png)

The configuration menu allows you to:

- **open overview after update**: if enabled, automatically open this window when you open **Your Guild** in the game menu ([keyboard shortcut](https://en.wiki.forgeofempires.com/index.php?title=Keyboard_shortcuts) ""G")
- **show searchbar**: toggles searchbar on tabs
- **show ex-members**: toggles display of ex-members on tabs
- **show 0-values (GE/GBG)**: players with 0 score in both will be highlighed in yellow
- **GE/GBG date format**: choose display format for seasons
- **delete ex-member after**: define data retention for ex-members
- **reset message counter**: toggle to yes to reset message counter
- **export data**: exports data into file named by tab name (in English), date, and time of export.

{% hint style="warning" %}
The Export button (CSV or JSON) exports only the data shown in the currently active tab.
{% endhint %}

## Usage

- Sort any column by clicking on its header.
- Data is refreshed when:
  - You open in-game Guild Menu (shortcut "G"), Member Overview tab
  - You open in-game Guild Menu (shortcut "G"), Guild Treasury tab
  - You visit a guildmate's city (eg. Great Buildings info)
  - You enter the [Guild Expedition](../gex/README.md#recording-data) screen
  - You open [Guild Battlegrounds](../gbg-players/README.md#recording-data) screen
- Changes are based on your last local update on the same computer.

## Tabs

Available tabs:
- [Guild Members](./guildmembers)
- [Eras](./eras)
- [Great Buildings](./greatbuilding)
- [Guild Buildings](./guildbuilding)
- [Treasury Goods](./treasury)