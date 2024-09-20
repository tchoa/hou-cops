# hou-cops
A few nodes to simplify things into Copernicus.
Some may be obsolete in a near future, when SideFX has improved it...

## Nodes
+ UDIM Select - *Digital Asset*
    * As stated, let you select an udim

+ Cop Import - *Recipe*
    * Imports another Cop
    * Let you select a single layer or expose all layers
    * Layer's name comes from e.g. null/collect output names

+ Heightfield Import - *Recipe*
    * Imports an Heightfield
    * Let you select a single layer or expose all layers

## Installation
1. Copy the *factocode_cops.json* into your package folder.
2. Inside this package file, edit the path to the package folder where you cloned this repo.
```e.g. "value": "${HOUDINI_USER_PREF_DIR}/factocode_cops"```