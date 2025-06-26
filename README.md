# Roll Dice – 3D Dice Roller

Identical-in-spirit remake of Google's "roll dice" widget.

## Quick start
1. Open `index.html` in a browser.  
2. Click **Adicionar** to add dice (choose type/qty).  
3. Click **Rolar 🎲**.

## Folders
- `models/` – put your custom 3D dice models (.glb).  
- `fonts/`  – custom fonts for UI or number textures.

## Swap to your 3D model
1. Copy `my_d20.glb` into `models/`.  
2. In `index.html`, replace the `geometryForFaces` switch with a GLTFLoader clone (see comments).

## Change number font
- **Texture method**: bake the font onto each face in Blender, export `.glb`.  
- **Dynamic canvas**: draw numbers on a `<canvas>` and use `CanvasTexture`.  

See comments in `index.html` for details.
