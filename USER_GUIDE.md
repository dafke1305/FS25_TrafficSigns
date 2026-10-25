# Traffic Signs — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.0.1** package linked in [this release](https://github.com/dafke1305/FS25_TrafficSigns/releases/tag/v1.0.0.1). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_TrafficSigns.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Place and edit a sign

1. Open **Construction > Decoration** and choose a direction sign. The release contains twenty models, including arrows, crossroads/roundabout boards, distance boards and overhead gantries.
2. Rotate and place it. Supports must stand beside the road and outside active fields; an overhead panel may span the road. Land ownership is not required for placement by this mod, but the support-ground checks still apply.
3. Leave your vehicle and walk to the sign. For an overhead gantry or cantilever, approach the edit point beside the **right support**.
4. Use **Edit destinations** in the contextual/F1 help. Choose the destination, road label, exit number or distance field that the model provides, enter the text and select **Apply**.
5. Repeat for other fields. Empty text hides that field. Each field accepts up to **48 characters**; long text shrinks to fit.

Editing requires membership of the sign's owner farm, or in-game server-administrator access, and proximity to its edit point. Text is saved with the placeable and synchronized to multiplayer clients.

## Model behaviour

- The arrow-shaped direction signs have editable text on the **front only**; their metal back is intentionally blank.
- Different models expose different fields; a one-panel sign does not gain four destinations through the editor.
- Prices range from 250 to 7,000; daily upkeep is zero.
- These are decorative wayfinding signs. They do **not** change AI traffic or GPS routes.

## Troubleshooting

| Problem | Check |
| --- | --- |
| No edit prompt | Get out, approach the correct support/edit point and check your farm or admin role. |
| Placement refused on a road/field | Move the foundations onto the verge or other permitted ground. Wait if ground data is still loading. |
| A painted road is not detected as a road | Detection depends on the map's native road data; painted textures alone cannot identify all roads. |
| Text is missing | Check that the field is not empty and that you are looking at the text-bearing face. |

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_TrafficSigns/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
