# Changelog  
  
| modName    | Antennas (ANTS) by DTPhantom                                      |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0+ARR                                                  |
| author     | DTPhantom and zer0Kerbal                                          |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207329-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Antennas)               |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Antennas)             |
| spacedock  | (https://spacedock.info/mod/98)                                   |
| ckan       | Antennas                                                          |

## Version 1.4.99.0-adoption `<Can You Hear Me Now?>`

* 17 Mar 2022
* For Kerbal Space Program [1.12.x]

* >>-- adoption by zer0Kerbal --<<

### Repo

* setup GitHub
* Update Antennas.version
* Update _release
* Update json's

### Folder

* Restructure and reorganize
* Rename /Patches to /Compatibility

### Compatibility Patches

* [AntennaRange.cfg] v1.1.0.0
* [RemoteTech.cfg] v1.1.0.0
* [Telemachus.cfg] v1.1.0.0
* rename to remove spaces in filenames
* Add :FOR[Antennas] to all patches
* add Header/Footer
* clean up whitespace

### Flags / Agency

* rename flags to remove spaces in filenames
* [PhantomAerospace-red.png]
* [PhantomAerospace-white.png]
* Resize from 256x160 to 512x360
* Create Agencies/[Agents.cfg]
  * create Phantom Aerospace
  * [PhantomAerospace.png]
  * [PhantomAerospace_scaled]
  * Agent Description needs fleshing out

### Parts

* Localization
  * Create agency
  * Localize
  * Parts to localize
    * [vhfBlade.cfg]
    * [hu6s125.cfg]
    * [yagiActual.cfg]
    * [yagiAntenna.cfg]
    * [helixAntenna.cfg]
    * [quadHelix.cfg]
* Assets
  * Create Assets folder
  * rename all models to reflect part name
    * [vhfBlade.mu]
    * [hu6s125.mu]
    * [yagiActual.mu]
    * [yagiAntenna.mu]
    * [helixAntenna.mu]
    * [quadHelix.mu]
  * update internal pointer from .png to .dds
  * rename corresponding [Tt]exture.dds to
    * [helixAntenna.mu]
      * [text000.dds]
    * [vhfBlade.mu]
      * [text001.dds]
    * [hu6s125.mu]
      * [text002.dds]
    * [yagiActual.mu]
      * [text003.dds]
    * [yagiAntenna.mu]
      * [text004.dds]
    * [quadHelix.mu]
      * [text005.dds]
  * updates #5 - Localization - Master
  * closes #6 - American English <us-en.cfg>
  * closes #21 - Part Localization
* Change
  * [Category] from Science to Communication
  * General Linting and reorganization
  * [attachRules] = 1,1,1,1,0 for all stackable parts
  * adjust attachment nodes
    * correct orientation
    * change size from 0 to 1
* Add
  * [tags]
  * @thumbs
  * [DRAG_CUBES]
  * preliminary [ModuleCargoPart] to all parts
* Specific part changes
  * [vhfBlade.cfg]
    * [ModuleDataTransmitter] added equal to C16S - SurfAntenna
    * [entryCost] was 7800, now is 800
    * [cost] was 1275, now is 400
    * crashTolerance[]] was 20, now is 10
  * [hu6s125.cfg]
    * [ModuleDataTransmitter]
      * added [antennaType] = DIRECT
      * added [antennaPower] = 750000]
    * [entryCost] was 7800, now is 780
    * [cost] was 1275, now is 350
    * crashTolerance[]] was 20, now is 11
  * [yagiActual.cfg]
    * [ModuleDataTransmitter]
      * added [antennaType] = DIRECT
      * added [antennaPower] = 1500000]
  * [yagiAntenna.cfg]
    * [ModuleDataTransmitter]
      * added [antennaType] = DIRECT
      * added [antennaPower] = 750000]
  * [helixAntenna.cfg]
    * [ModuleDataTransmitter]
      * added [antennaType] = DIRECT
      * added [antennaPower] = 750000]
  * [quadHelix.cfg]
    * [ModuleDataTransmitter]
      * added [antennaType] = DIRECT
      * added [antennaPower] = 500000]

### GameData

* Localization folder 📁
* Localization\ [readme.md][URL:lclztn] 🗃️
* Localization\ [quickstart.md][URL:qs] 🗃️

### Documentation

* Create
  * [readme.md] 🔢
  * [release.md] 🧾
  * [ManualInstallation.md]
  * [Attributions.md]

#### docs/

* Create
  * docs/
    * [localization.md]
    * [PartInvoice.md]
    * [404.md]
    * [Attributions.md]
    * [index.md]
    * [LegalMumboJumbo.md]
    * [Localizations.md]
    * [ManualInstallation.md]
    * LegalMumboJumbo/
      * [FORUM-01.png]
      * [License.md]
    * ReleaseNotes/
      * [1.4.99.0.md]

### Status

* Issues
  * closes #4 - 1.4.99.0 Social Media
  * closes #3 - 1.4.99.0 Update Documentation
  * closes #2 - 1.4.99.0 Verify Legal Mumbo Jumbo
  * closes #1 - Antennas 1.4.99.0-adoption <Can You Hear Me Now?>

## Version 1.4 (12 May 16)

* Fixed configs to stop breaking Antenna Range

## Version 1.3 (16 Feb 16)

* Fixed Antenna Range file for Scimitar antenna
* Uploaded the mod to Curse with the shutdown of KerbalStuff

## Version 1.2 (27 Oct 15)

* Renamed yagi antenna to log periodic to more accurately represent what it is.
* Fix node attach rules for antennas, they should attach the right direction now.
* Added patches for Antenna Range compatibility
* Added 2 new antennas
  * An actual yagi-antenna that has 40Gm of range, perfect for covering the inner solar system from Kerbin
  * A wrap around omni antenna for 1.25m parts.

## Version 1.1

* fixed typos in Telemachus module manager patches

## Version 1.0

* Intial release

* >>-- creation by DTPhantom --<<

<!-- CC BY-NC-ND 3.0 Unported zer0Kerbal -->