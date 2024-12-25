> [!WARNING]
> Baggage is still under development and has not been released yet. The current source is equivalent to Satchel.

<div style="text-align: center;">
    <img alt="Baggage logo" src="assets/BaggageDark.png#gh-dark-mode-only">
    <img alt="Baggage logo" src="assets/BaggageLight.png#gh-light-mode-only">
</div>

<div style="text-align: center;">

  [![Release][shield-release]][../../releases]
  [![License][shield-license]][./LICENSE.txt]

  [![Download-CreatorStore][mb-robloxdev]][robloxdev]
  [![Download-GitHub][mb-github]][../../releases/latest]
</div>

Baggage is a modern open-source alternative to Roblox's default backpack. Baggage aims to be more customizable and easier to use than the default backpack while still having a vanilla feel.

Baggage is a fork of [Satchel](satchel).

Installation of Baggage is as simple as dropping the module into your game and setting up a few properties if you like to customize it. It has a familiar feel and structure as to the default backpack for ease of use for both developers and players.

---

## ⭐ Features

Baggage looks similar to [Roblox's new Chrome UI](devforum-chromeui), while still retaining the original functionality of the built-in backpack.

<div style="text-align: center;">
  <img alt="Baggage on computer matching Roblox's UI design" src="./assets/" style="width: 49%;">
</div>

### Highly Customizable & Versatile

Baggage is highly customizable & adjustable with instance attributes support allowing you to customize the behavior and appearance of Baggage. Change the color, transparency, behavior and more of it's elegantly designed UI.

<div style="text-align: center;">
  <img alt="Baggage with a customized UI to have a red tint" src="./assets/" style="width: 49%;">
</div>

### Improved Mobile Experience

Baggage expands the mobile experience by doubling the number of slots so that mobile players are not at a disadvantage.

<div style="text-align: center;">
  <img alt="Baggage on mobile with 6 hotbar slots" src="./assets/" style="width: 49%;">
</div>

### Topbar Plus Support

Baggage supports [TopbarPlus](devforum-topbarplus) to restore original functionality of the old backpack. This feature can be turned off in Baggage, unlike Satchel.

<div style="text-align: center;">
  <img alt="Baggage inventory topbar button along with Roblox's topbar" src="./" style="width: 49%;">
</div>

## 🔽 Installation

Installation of Baggage is easy and painless. Baggage is a drag-and-drop module that works out of the box and with easy customization. Below are different ways to get you to download and install Baggage.

<details>

<summary>**1. Creator Store (Recommended)**</summary>

1. Get Baggage from the [Creator Store](robloxdev).

2. Open or locate [Toolbox](rs-toolbox).

3. Find and insert Baggage in [Inventory](rs-inventory)

4. Move Baggage into [StarterPlayerScripts](rs-sps).

</details>

<details>

<summary>2. GitHub Release Binary</summary>

> [!WARNING]
> The GitHub release binary does not have package support, which means you will have to update Baggage manually if you implement it this way.

1. Download `Baggage.rbxmx` file from [the latest release](../../releases/latest).

2. Right click on [StarterPlayerScripts](rs-sps) and click on `"Insert from file..."`

3. Find/select `Baggage.rbxmx` and click `Open`

</details>

<!--
## 📖 Documentation

<details>

<summary>Attributes</summary>

Satchel supports instance attributes allowing you to change and customize many aspects including various behaviors in a friendly easy-to-use interface without having to touch any code. Below see all attributes.

| Attribute | Description | Default |
| :--- | :--- | :--- |
| BackgroundColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the background color of the default inventory window and slots. | `[25, 27, 29]` |
| BackgroundTransparency: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the background transparency of the default inventory window and slots. | 0.3 |
| CornerRadius: [`UDim`](https://create.roblox.com/docs/reference/engine/datatypes/UDim) | Determines the radius, in pixels, of the default inventory window and slots. | `0, 8` |
| EquipBorderColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the equip border when a slot is equipped. | `[255, 255, 255]` |
| EquipBorderSizePixel: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the pixel width of the equip border when a slot is equipped. | `5` |
| FontFace: [`Font`](https://create.roblox.com/docs/reference/engine/enums/Font) | Determines the font of the default inventory window and slots. | `Builder Sans` |
| InsetIconPadding: [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) | Determines whether or not the tool icon is padded in the default inventory window and slots. | True |
| OutlineEquipBorder: [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) | Determines whether or not the equip border is outline or inset when a slot is equipped. | True |
| TextColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the text in default inventory window and slots. | `[255, 255, 255]` |
| TextSize: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the size of the text in the default inventory window and slots. | `14` |
| TextStrokeColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the text stroke of text in default inventory window and slots. | `[0, 0, 0]` |
| TextStrokeTransparency: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the transparency of the text stroke of text in default chat window and slots. | 0.5 |

</details>

<details>

<summary>Methods</summary>

Satchel offers access to some of its internal methods and events for scripting purposes. Below see a table with all the methods available.

| IsOpened(): [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) |
| :--- |
| Returns whether the inventory is opened or not. |

| SetBackpackEnabled(enabled: boolean): `void` |
| :--- |
| Sets whether the backpack gui is enabled or disabled. |

| GetBackpackEnabled(): [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) |
| :--- |
| Returns whether the backpack gui is enabled or disabled. |

| GetStateChangedEvent(): [`RBXScriptSignal`](https://create.roblox.com/docs/reference/engine/datatypes/RBXScriptSignal) |
| :--- |
| Returns a signal that fires when the inventory is opened or closed. |

</details>
!-->

[shield-release]:       https://img.shields.io/github/v/release/theletron/Baggage?include_prereleases&logo=robloxstudio&logoColor=white&color=00a2ff&style=for-the-badge
[shield-license]:       https://img.shields.io/github/license/theletron/Baggage?logo=mozilla&color=00a2ff&style=for-the-badge
[mb-robloxdev]:         https://gist.githubusercontent.com/cxmeel/0dbc95191f239b631c3874f4ccf114e2/raw/bb4634715f95ebb209b4e0bcdd4d2d98fe64c64c/roblox_dev.svg
[mb-github]:            https://gist.githubusercontent.com/cxmeel/0dbc95191f239b631c3874f4ccf114e2/raw/bb4634715f95ebb209b4e0bcdd4d2d98fe64c64c/github.svg

[robloxdev]:            https://create.roblox.com
[satchel]:              https://github.com/RyanLua/Satchel

[rs-toolbox]:           https://create.roblox.com/docs/studio/toolbox
[rs-inventory]:         https://create.roblox.com/docs/projects/assets/toolbox#inventory
[rs-sps]:               https://create.roblox.com/docs/reference/engine/classes/StarterPlayerScripts

[devforum-topbarplus]:  https://devforum.roblox.com/t/1017485
[devforum-chromeui]:    https://devforum.roblox.com/t/3215981
