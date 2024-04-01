# KiCAD Components

A repository of my customer KiCAD symbos, footprints and 3D models.

KiCAD version: 8

## Setup

1. Clone the Repo, and make note of the path
2. Open KiCAD
3. Click _Prerences_ > _Configure Paths_
4. Create a path `CUSTOM_3DMODEL_DIR` pointed to `$PATH/3dmodels`
4. Create a path `CUSTOM_FOOTPRINT_DIR` pointed to `$PATH/footprints`
4. Create a path `CUSTOM_SYMBOL_DIR` pointed to `$PATH/symbols`

### Symbols

1. Open the Symbol Editor
2. Click _Preferences_ > _Manage Symbol Libraries_
3. Add each library `${CUSTOM_SYMBOL_DIR}/$LIBRARY_NAME`

### Footprints

1. Open the Footprint Editor
2. Click _Preferences_ > _Manage Footprint Libraries_
3. Add each library `${CUSTOM_FOOTPRINT_DIR}/$LIB`


