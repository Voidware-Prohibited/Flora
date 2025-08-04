<h1 align="center">Flora</h1>

<p align="center">
<img src="Flora.png" alt="Flora">
</p>

<p align="center">
     <a href="https://github.com/Voidware-Prohibited/Flora/commits/master"><img src="https://img.shields.io/github/last-commit/Voidware-Prohibited/Flora.svg?style=flat-square&logo=github&logoColor=white" alt="GitHub last commit"></a>&nbsp;
     <a href="https://github.com/Voidware-Prohibited/Flora/issues"><img src="https://img.shields.io/github/issues-raw/Voidware-Prohibited/Flora.svg?style=flat-square&logo=github&logoColor=white" alt="GitHub issues"></a>&nbsp;
     <a href="https://github.com/Voidware-Prohibited/Flora/pulls"><img src="https://img.shields.io/github/issues-pr-raw/Voidware-Prohibited/Flora.svg?style=flat-square&logo=github&logoColor=white" alt="GitHub pull requests"> </a>&nbsp;
     <a href="https://github.com/Voidware-Prohibited/Flora/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-silver.svg?style=flat-square&logo=github&logoColor=white" alt="MIT License"></a>
</p>
<p align="center">
     <a href="https://github.com/sponsors/colorindarkness"><img src="https://img.shields.io/github/sponsors/colorindarkness.svg?style=flat-square&logo=github&logoColor=white" alt="Become a Sponsor"></a>&nbsp;
     <a href="https://www.patreon.com/colorindarkness"><img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dcolorindarkness%26type%3Dpatrons&style=flat" alt="Become a Patron"></a>&nbsp;
     <a href="https://ko-fi.com/colorindarkness"><img alt="Support me on Ko-fi" src="https://img.shields.io/badge/support_me_on-Ko--fi-red?link=https%3A%2F%2Fko-fi.com%2Fcolorindarkness"></a>&nbsp;
     <a href="https://liberapay.com/colorindarkness"><img alt="Support me on Liberapay" src="https://img.shields.io/badge/support_me_on-liberapay-yellow?link=https%3A%2F%2Fliberapay.com%2Fcolorindarkness%2F"></a>
</p>

A kit of fully functional, customizable and optimized foliage assets with compatible licenses gathered from the internet, prepared and standardized with Wind support for Unreal Engine 5. Check out the parent project [Target Vector](https://github.com/Voidware-Prohibited/TargetVector).

_Flora is under heavy development, many features may not be finished or production-ready_.

# Features

- Customizable Material setup with Color Map for up to 3 colors.
- Vertex Weight Painted for Unreal Engine 5 Wind system.
- Channel Packed Maps for minimal draw calls.

**Flora Categories**

- Grass
- Foliage
- Shrub
- Ground Cover

**Current Biomes**

- Beach
- Tropical/Rainforest
- Grassland
- Desert _In Progress_

**Planned Features**
- Coniferous Forest
- Decidious Forest
- Stumps
- Fallen Trees
- Rocks/Stones

# Installation

Clone or Download into a folder named _Flora_ in your existing projects Plugins folder.

The [Flora-Assets](https://github.com/Voidware-Prohibited/Flora-Assets) repo contains all the Source Asset files, including the Blender files, Photoshop files, exported image files and audio files.

# Usage

## Unreal Engine

Basic: In Foliage Mode, simply add the desired assets to your Foliage brush and begin painting on the landscape.

Intermediate: Add desired assets as Grass assets to a Landscape Auto Material.

Advanced: Add desired assets as Instanced Foliage Actor assets to a Landscape Auto Material for Customization and Interactability.

## Material and Texture Setup

All Textures are Channel Packed into the RGBA Channels. Targa (.TGA) files are used whenever useful to store data in the Alpha channel.

A Color Map is used to allow for customization of up to 3 colors per material instance.

Make Material Instances for countless color and parameter variations for use in Instanced Foliage Actors.

**Maps**
Some assets may not use all maps/channels.

- Diffuse (RGB) and Alpha _filename_\_DA.(tga/png)
- Color Map (RGB) _filename_\_CM.(tga/png)
- Ambient Occlusion (R), Roughness (G), Metallic (B), Specular (Alpha) _filename_\_AORMS.(tga)
- Normal Map (RG), Height/Displacement Map (B), Subsurface Scattering Map (Alpha) _filename_\_NHSS.(tga)

# Settings

An example Material setup is included in Content that utilizes up to 3 customizable colors and other parameters.

# Contributions

[_Contibutors and PRs are welcome via Github!_](https://github.com/Voidware-Prohibited/Flora/pulls)

# License

[Original content and code in this repository is under the Custom MIT license LICENSE.md](LICENSE.md). Original Content listed in the Attributions are covered by their respective licenses.

# Attributions

[Attributions listed in ATTRIBUTIONS.md](ATTRIBUTIONS.md)

# Special Thanks

[Freesound](https://freesound.org/)

[SketchFab](https://sketchfab.com/)
