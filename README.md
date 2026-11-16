# simpleGamemodes

Fabric mod for Minecraft 1.21.11. Adds gamemode shortcuts:

| Command | Does |
|---------|------|
| `/gms`  | `/gamemode survival` |
| `/gmc`  | `/gamemode creative` |
| `/gma`  | `/gamemode adventure` |
| `/gmsp` | `/gamemode spectator` |

Same permissions as vanilla `/gamemode` (op / cheats). Requires Fabric API. Works server-side, so it also runs on dedicated servers.

## Build
Push to GitHub: the workflow in `.github/workflows/build.yml` builds the jar. Download it from the Actions run's "simplegamemodes" artifact. Pushing a tag like `v1.0.0` also creates a Release with the jar.
