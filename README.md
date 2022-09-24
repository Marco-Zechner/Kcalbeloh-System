# Kcalbeloh System

![Imgur](https://i.imgur.com/KFlHVFt.png)
Kcalbeloh System adds a new black hole system to Kerbal Space Program. 

## Contents
   - [**System Map**](https://github.com/jcyuan06/Kcalbeloh-System#system-map)
   - [**Installation**](https://github.com/jcyuan06/Kcalbeloh-System#installation)
      - [Install Automatically from CKAN](https://github.com/jcyuan06/Kcalbeloh-System#install-automatically-from-ckan)
      - [Install Manually](https://github.com/jcyuan06/Kcalbeloh-System#install-manually)
      - [After Installation (Please read!)](https://github.com/jcyuan06/Kcalbeloh-System#after-installation-please-read)
      - [Installation Checklist](https://github.com/jcyuan06/Kcalbeloh-System#installation-checklist)
   - [**Mod Settings**](https://github.com/jcyuan06/Kcalbeloh-System#mod-settings)
      - [Wormholes](https://github.com/jcyuan06/Kcalbeloh-System#wormholes)
      - [Home Switch](https://github.com/jcyuan06/Kcalbeloh-System#home-switch)
      - [Distance](https://github.com/jcyuan06/Kcalbeloh-System#distance)
      - [Rescale](https://github.com/jcyuan06/Kcalbeloh-System#rescale)
   - [**Compatibility**](https://github.com/jcyuan06/Kcalbeloh-System#compatibility)
      - [RSS Compatibility](https://github.com/jcyuan06/Kcalbeloh-System#how-to-make-it-compatible-with-realsolarsystem)
   - [**Recommended Mods**](https://github.com/jcyuan06/Kcalbeloh-System#recommended-mods)
   - [**FAQs**](https://github.com/jcyuan06/Kcalbeloh-System#faqs)
   - [**Contacts**](https://github.com/jcyuan06/Kcalbeloh-System#contacts)
   - [**License**](https://github.com/jcyuan06/Kcalbeloh-System/blob/main/GameData/KcalbelohSystem/License.md#attribution-noncommercial-noderivatives-40-international)
# System Map
<details>
   <summary> Are you sure you want to spoil it? </summary>
   <p>
   <img src=/KcalbelohSystemMap6k.png>
   </p>
 </details>
 
# Installation
![Imgur](https://i.imgur.com/wRbpAsq.png)
### Install Automatically from CKAN
Not available for beta release.

### Install Manually
1. **Install Kcalbeloh System**
   * [**Download**](https://github.com/jcyuan06/Kcalbeloh-System/releases) the newest version of Kcalbeloh System, extract and put all the contents in /GameData to your KSP /GameData folder.
   * If you are updating this mod, make sure you delete the previous version completely before installing the new version.  
2. **Install Dependencies**
   * [**Kopernicus**](https://forum.kerbalspaceprogram.com/index.php?/topic/200143-181-1122-kopernicus-stable-branch-last-updated-november-25th-2021/): for creating custom celestial bodies.
   * [**Singularity**](https://forum.kerbalspaceprogram.com/index.php?/topic/193709-wip18x-112x-singularity-black-hole-shaders/#comment-3782330): for blackhole and wormhole shaders.   
   * [**KSPCommunityFixes**](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-18-112-kspcommunityfixes-bugfixes-and-qol-tweaks/): for bug fixes.
3. **Install Visuals**  
The planet pack works fine without visual mods, but it will lose a large part of its aesthetic.
   * [**EVE Redux**](https://forum.kerbalspaceprogram.com/index.php?/topic/196411-19-112-eve-redux-performance-enhanced-eve-maintenance-v11151-07112021/): for clouds, dust storms, and auroras.
   * [**Scatterer**](): for realistic atmosphere, oceans, and sun flares.  
### After Installation (Please read!)
In KSP 1.12.x, the stock maneuver planning tool can cause severe lag/stutter in planet mods, so it's strongly recommended to disable it:
   * Press ESC in game and press the 'Settings' button. Then disable the maneuver tool in the setting menu, under KSP Community Fixes section. See below:
   
![Imgur](https://i.imgur.com/z89SQdm.gif)
### Installation Checklist
   After a complete installation, the GameData folder should at least have the following contents:
   * 000_Harmony
   * EnvironmentalVisualEnhancements
   * KcalbelohSystem
   * Kopernicus
   * KopernicusExpansion
   * KSPCommunityFixes
   * ModularFlightIntegrator
   * Scatterer
   * Singularity
   * ModuleManager.4.2.2.dll
# Mod Settings
![Imgur](https://i.imgur.com/Noi9Uym.pngg)
Go to `Kerbal Space Program/GameData/KcalbelohSystem/` and open `Kcalbeloh System Settings.cfg`.

### Wormholes
`Wormholes = `: whether to have wormholes connecting stock solar system and Kcalbeloh system.  
   - `True`: (default) enable the wormholes.
   - `False`: disable the wormholes.

### Home Switch
`HomeSwitch = `: whether to move KSC to Kcalbeloh system. 
   - `False`: (default) keep KSC on Kerbin.
   - `Suluco`: move KSC and other launch sites and airfields to Suluco.
   - `Efil`: move KSC and other launch sites and airfields to Efil.
   - Home switch is NOT compatible with system-replacement planet mods (Beyond Home, GPP, RSS, etc).
   - Do **NOT** load any saved game after changing home switch setting.

### Distance
`DistanceFactor =`: moving Kcalbeoh System closer or further to stock system.  
   - `1`: (default) keep the default distance (271.8 Tm).
   - `0.1`: 0.1x default distance.
   - `10`: 10x default distance.
   - `100`: 100x default distance.

### Rescale
`Rescale = `: rescale the system to 2.5x or 10x size.  
   - `1`: (default) No rescales applied. It has the same scale with stock system.
   - `2.5`: 2.5x scale. If JNSQ is installed, this value will be forced.
   - `10`: 10x scale (realistic scale). If RealSolarSystem is installed, this option will be forced.
   - This setting needs [Sigma Dimensions](https://github.com/Sigma88/Sigma-Dimensions) installed.
   - Rescale only applies to celectial bodies from this mod.
# Compatibility
![Imgur](https://i.imgur.com/hPm4c7b.png)
Kcalbeloh System provides support with:  
   - Environmental Visual Enhancements
   - Scatterer
   - Parallax (Needs Parallax Stock Textures)
   - Community Resource Pack
   - SpaceDust
   - Kerbalism
   - PlanetShine   

Kcalbeloh System is compatible with:
   - Most visual mods (AVP, Spectra, SVE...)
   - Most planet mods (Beyond Home, OPM, GPP...)
   - RealSolarSystem, but requires some minor adjustments. See the next session.   

Kcalbeloh System is NOT compatible with:
   - Principia

### How to make it compatible with RealSolarSystem?
1. Download `RSSKopernicusSettings.cfg` in the [download page](https://github.com/jcyuan06/Kcalbeloh-System/releases).
2. Put it to `Kerbal Space Program/GameData/RealSolarSystem/` and replace the original file. 
3. Install [Sigma Dimensions](https://github.com/Sigma88/Sigma-Dimensions).

Note: When installing Kcalbeloh System and RealSolarSystem together, 10x rescale will be forced on Kcalbeloh System.

# Recommended Mods
![Imgur](https://i.imgur.com/Wz54y0w.png)
   - [**Near Future Technologies**](https://forum.kerbalspaceprogram.com/index.php?/topic/155465-most-112x-near-future-technologies-august-26/)  
   Advanced electric engines, nuclear reactors, large solar panels, antenna, and more!
   - [**Far Future Technologies**](https://forum.kerbalspaceprogram.com/index.php?/topic/199070-112x-far-future-technologies-august-23-new-engine/)  
   Fission, fusion, and antimatter engines!
   - [**Better Time Warp**](https://forum.kerbalspaceprogram.com/index.php?/topic/154935-112x-bettertimewarpcontinued-customizable-time-warp-and-lossless-physics-warp/)  
   
   - [**Extraplanetary Launchpads**](https://forum.kerbalspaceprogram.com/index.php?/topic/54284-112-extraplanetary-launchpads-v6993/)  
   Build your vessels in another planet!

# FAQs
![Imgur](https://i.imgur.com/gwV8mR9.png)
1. **Does it replace the Kerbol system or add a new system?**  
It adds a new system without any change to the Kerbol system. But it also offers home switch options which allow you to move KSC to habitable planets in Kcalbeloh system. For more information on home switch, [click here](https://github.com/jcyuan06/Kcalbeloh-System#home-switch).

2. **Is it based on the movie Interstellar?**  
Yes, but no. Although some ideas of the mod are inspired by Interstellar, the goal of the mod is not to facsimile the Gargantua system from Interstellar, but to create a unique star system.

3. **Is it compatible with other planet packs?**  
Yes, it is compatible with most planet packs but it still needs further testing. Let me know if you have any issues.

4. **Is it compatible with Real Solar System?**  
Yes, but you need to download a config file. See [here](https://github.com/jcyuan06/Kcalbeloh-System#how-to-make-it-compatible-with-realsolarsystem).

5. **Is it compatible with other visual mods?**  
Yes, it is compatible with most visual mods for stock system, such as Astronomer's Visual Pack, Spectra, and Stock Visual Enhancement.

6. **What is a wormhole? How can I use it?**  
A wormhole is a structure linking disparate points in spacetime. In KSP, a wormhole functions like a celestial body with its mass and SOI. To traverse the wormhole, you need to lower your periapsis below 30 km. After you reach the periapsis, you will jump to the other star system.

# Contact
![Imgur](https://i.imgur.com/eFFC7Fe.png)
[KSP Forum](https://forum.kerbalspaceprogram.com/index.php?/topic/203753-wip-112x-kcalbeloh-system-planet-pack-beta-12-a-journey-to-a-black-hole-may-02-2022/)  
[Discord Server](https://discord.gg/Crmy8KgqK2) 
