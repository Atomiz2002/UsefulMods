# Useful Mods
Note: Alkyaly has stopped maintaining their list, and they have given me the responsibility to maintain their list ([original list here](https://gist.github.com/alkyaly/02830c560d15256855bc529e1e232e88)).

A list of useful mods for most commonly-played versions.<br>

Any suggestions/complaints?<br>
Join our [discord](https://discord.gg/8nzHYhVUQS) or submit an issue (or a pull request fixing it!)

## Mods Under Consideration
Everything that is under consideration to be added is found [here](https://docs.google.com/document/d/127YtDboB7mQIH3SK8jd4d3_I7ur0LPHT46l9I1zRrwA/edit?usp=sharing).<br>
Keep in mind that nothing in the document is screened for harmful code (or malware). Download at your own caution.

## Version List
| Version | Performance | Bugfixes |
| :-: | :-: | :-: |
| 1.18.x | [✔️ Available](Performance/Performance118.md) | [✔️ Available](BugFixes/BugFixes118.md) |
| 1.17.x | [✔️ Available](Performance/Performance117.md) | [✔️ Available](BugFixes/BugFixes117.md) |
| 1.16.x | [✔️ Available](Performance/Performance116.md) | [⚠️ WIP](BugFixes/BugFixes116.md)
| 1.15.x | [✔️ Available](Performance/Performance115.md) | [⚠️ WIP](BugFixes/BugFixes115.md)
| 1.12.x | [✔️ Available](Performance/Performance112.md) | [⚠️ WIP](BugFixes/BugFixes112.md)
| 1.8.9 and below | [✔️ Available](Performance/PerformanceOld.md) | [⚠️ WIP](BugFixes/BugFixesOld.md)

## External Software
| Theme |
| :---: |
| [Launchers](Software/SoftwareLaunchers.md) |
| [Bukkit, Spigot, etc.](Software/SoftwareBukkitSpigotETC.md) |
| [Graphical](Software/SoftwareGraphical.md) |
| [World Management](Software/SoftwareWorldManagement.md) |
| [Server Management](Software/SoftwareServerManagement.md) |

## Labels
Labels are used to give you a better understanding of how a mod may act.

| Name | Meaning |
| :--: | :-----: |
| Alpha | Mod is in alpha and therefore might be unstable. |
| Unstable | Mod is unstable and may act unpredictably. |
| Corruption | Mod has a chance to corrupt save files. |
| Incompatible | Mod is incompatible with some mods. |
| Buggy | Mod is buggy. |
| Reverse Features | Mod takes away features for sake of performance or bugfixes. |
| Configuration Needed | Mod needs to be configured to act at its best. |

## Severity Level
Severity Level is used alongside labels for a clearer understanding of how severe the issue is.

| Level | Meaning |
| :---: | :-----: |
| 1 | Low chance to affect user |
| 2 | Low to medium chance to affect user |
| 3 | Medium chance to affect user |
| 4 | Medium to high chance to affect user |
| 5 | High chance to affect user |
| 6 | Very high chance to affect user |
| 7 | Will affect user |
| ? | Level of severity is unknown |

## Extra Information
You might find some superscripted numbers around the repository. These are used to tell extra information about the mods that labels and danger levels do not apply to.
&nbsp;

###### ¹ The mod should work if [Mixin-0-7-0-8-Compatibility](https://www.curseforge.com/minecraft/mc-mods/mixin-0-7-0-8-compatibility) is applied. 
###### ² Cull Particles isn't needed anymore in newer Forge versions, as it was implemented in Forge.
###### ³ Do not blame me if you didn't read this notice. *If you try to load a older world in a newer instance of the game, and you have one of these mods installed, bad things will happen*, make sure to uninstall the mod first.
###### ⁴ Some of the mods that have Sodium as an incompatibility, might work if you use [Indium](https://modrinth.com/mod/indium).
###### ⁵ AI Improvements newer versions (1.14+) don't have as much impact as the older versions have, since in newer versions of Minecraft, a lot of fixes to the AI are implemented ([Sources: Curseforge page FAQ, [Dev](https://media.discordapp.net/attachments/254806806516203520/831525756143534150/unknown.png)]).
###### ⁶ Halogen has issues with Forge's ExplosionEvent, see [sodium-forge#33](https://github.com/spoorn/sodium-forge/issues/33).
###### ⁷ These mods also work on 1.17.x , despite having only 1.16 and 1.18 releases in curseforge, no workarounds needed. Install them like any other mods and your fabric loader won't complain about missing dependencies.