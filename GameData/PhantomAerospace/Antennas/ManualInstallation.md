---
permalink: /ManualInstallation.html
title: ManualInstallation
---

<!-- ManualInstallation.md v1.1.0.0
Antennas (ANTS)
created: 01 Oct 2019
updated: 02 Mar 2022 -->

<!-- based upon work by Lisias -->

# Antennas (ANTS)

Adds six new antennas that are compatible with both Antenna Range, Remote Tech and Telemachus to Kerbal Space Program.

Antennas under zer0Kerbal's management!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/PhantomAerospace/Antennas`
* Extract the package's `Notes/` folder into your KSP's as follows:
  * `<PACKAGE>/PhantomAerospace/Antennas` --> `<KSP_ROOT>/GameData/PhantomAerospace/Antennas`
    * Overwrite any preexisting file.
    * )optional( restore from backup to `<KSP_ROOT>/GameData/PhantomAerospace/Antennas/NotePad`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/PhantomAerospace/Antennas`
* Extract the package's `GameData/` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/PhantomAerospace/Antennas` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
    * )optional( restore from backup to `<KSP_ROOT>/GameData/PhantomAerospace/Antennas/NotePad`

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [PhantomAerospace]
      [Antennas]
        [Agencies]
          ...
        [Assets]
          ...
        [Compatibility]
          ...
        [Flags]
          ...
        [Localization]
          ...
        [Parts]
          ...
          [@thumbs]
            ...
        1.4.99.0.htm
        Antennas.version
        CC-BY-NC-SA-4.0.txt
        changelog.md
        License.txt
        readme.htm
    ...
  KSP.log
  ...
```

### Dependencies

* none

### Installation Directions

***Use***
  CurseForge/OverWolf App (currently does not install dependencies) [^3]  

  <a href="https://download.curseforge.com/">
    <img src="https://www.overwolf.com/brand-guidelines/img/logo2.svg" alt="CurseForge/OverWolf App" width="15%" height="15%">
</a>

or [![CKAN][CKAN:img]][CKAN:url] [^3]  

### Dependencies

* [Kerbal Space Program][KSP:url] [![Kerbal Space][KSP:shd]][KSP:url] [^1]

### Supports

* [Module Manager /L][thread:mm] [^2] *only required to use the Compatibility patches*
* [AntennaRange][thread:ar]
* [RemoteTech][thread:rt]
* [Telemachus][thread:tele]

[thread:ar]: http://forum.kerbalspaceprogram.com/index.php?/topic/51591-* "AntennaRange"
[thread:mm]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager"
[thread:rt]: http://remotetechnologiesgroup.github.io/RemoteTech/ "RemoteTech"
[thread:ckan]: https://forum.kerbalspaceprogram.com/index.php?/topic/154922-* "CKAN"
[thread:tele]: https://forum.kerbalspaceprogram.com/index.php?/topic/144482-* "Telemachus"
<!--- CKAN -->
[CKAN:img]: https://i.postimg.cc/x8XSVg4R/sj507JC.png "CKAN"
[CKAN:url]: http://forum.kerbalspaceprogram.com/index.php?/topic/197082-* "CKAN"
[CKAN:shd]: https://img.shields.io/badge/CKAN-Antennas-white.svg?labelColor=E32811&style=plastic "CKAN"
