
# FOSS Graphics

- All programs are cross-platform.

## 3D Programs

### Blender

- For 3D assets.
- Version 2.79 is perfect for game assets, while 2.8 is a huge overhaul primarily aimed at animators (with big plans for game assets too).
- Version 2.79 is recommended until the official release of 2.8 but beginning animators may prefer to start with 2.8
- Can also be used to bake normalmap textures and procedural textures (though the workflow is not straight-forward due to Blender's high number of features; these things will improve in the future).

### Wings3D

- Simpler 3D option which is often loved by beginners.
- Designed for modeling with subdivision, the key missing feature is animation support.
- Best used for exporting static Wavefront OBJ meshes (when working with Godot).

## 2D Programs

### GIMP

- Good procedural texture rendering (Filters) in 2.8
- *Great* procedural texture rendering in 2.10
- Great all-around 2D editor for raster graphics (pixel graphics).
- Graphics tablet configuration can be difficult (I like to disable autosave input config, and manually save the pen config, plus let mouse and pen use same brush options).
- Many plugin options, including *heightmap*->*normalmap* conversion and G'MIC.
- Can export animated GIFs but has zero animation support (feel free to try out the GIMP Animation Package which I had no luck with).

### Inkscape

- Standard vector graphics software, base standard for SVG (Scalar Vector Graphics) images.
- Vector uses shapes and numbers to define images, which web browsers and other applications use to render the image every time.
- The image (SVG) is the source file.
- Anti-aliasing is a document property, and affects rendering.
This applies to exporting and the SVG itself because the property is saved within the SVG XML.

### MyPaint

- Great for concept art, or drawing your ideas.
- Great brush engine for graphics tablets.
- Expanding canvas is not limited by preset canvas size.
- Fullscreen mode automatically hides the UI giving a fullscreen canvas. Let the ideas flow.
- MyPaint library lets other programs use the brush engine (as seen in GIMP 2.10). The expanding canvas still makes MyPaint a must-have.

### Krita

- Critically acclaimed brush engine works great with mouse or graphics tablet.
- Full tablet support.
- Vector and raster graphics support.
- 2D animation editing included.
- Unique tool interactions (such as with the Bezier tool) intended for creative artists.
- Procedural texture generation available through G'MIC. *heightmap*->*normalmap* conversion included with Krita.
- Relatively high system requirements (Qt) may push some users to a GIMP and Inkscape toolkit.

# Other

### Pencil2D

- Mostly unrelated to game asset design, but it's a fun and simple 2D animator.
- Includes audio track support.
- Blender 2.8 is a more popular (and powerful) option. The Pencil2D devs don't intend to have the latest and greatest features, just Pencil2D features.


## File Compression

### Linux / Mac

- Most formats are supported by default, or easily supported with an install from repository.

### Windows

- Just get Peazip. It does it all and more (such as Peazip-specific file formats).
- Other odd features like "Secure file delete" are typically included with Peazip.
- All the general utilities in one spot.
