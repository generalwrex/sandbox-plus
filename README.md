# SandboxPlus, a base gamemode for S&box

It closely follows [Facepunch's Sandbox gamemode](https://github.com/Facepunch/sandbox), with additions to make it more extendable by other modules (adding events, publicizing UI globals, etc), while staying unopinionated/light. This module is primarily aiming to become a "Gmod 2", replicating the functionality found in Gmod's Sandbox gamemode (with improvements).

## Improvements over Facepunch/sandbox:

### Gameplay
- Constraint tool: an omni-tool with all your classic Gmod constraints (weld/axis/rope/elastic/slider/ballsocket)
- Material tool
- Toolgun model (wip)
- DynPlates spawnmenu: like PHX, but dynamic, fully customizable sizes using procedural meshes
- UI tool panels, including ModelSelector with extendable `.spawnlist`'s

### Extensiblility

- `IStopUsing` entity interface
- `SandboxPlayer.OnSimulate` event, so ents can subscribe to keypresses
- Sandbox.Hooks.Entities.OnSpawned event, Sandbox.Hooks.Undos.OnAddUndo event

## Addons for SandboxPlus

- [Wirebox](https://github.com/wiremod/wirebox), playable as [Sandbox With Wirebox](https://asset.party/wiremod/sandboxpluswire)
- [Undo Manager](https://github.com/Nebual/undo-manager) (outdated, will probably just add to the base gamemode)
- [Napkins-Chat](https://github.com/Nebual/napkins-chat) (outdated)

## Contributing

PR's are appreciated!
