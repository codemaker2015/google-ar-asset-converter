Google ARCore Asset Converter
=====================

## Getting Started

This repository contains Sceneform binaries to generate .SFA and .SFB files to import on any ARCore projects.

## Generating assets

### For Ubuntu,

    $ ./sceneform_sdk/linux/converter -a -d --mat ./sceneform_sdk/default_materials/obj_material.sfm --outdir ./output/ ./input/andy.obj

### For Windows,
    
    sceneform_sdk\windows\converter -a -d --outdir output input\model.fbx
    
### For Mac,
    ./sceneform_sdk/mac/converter -a -d --outdir output input/model.fbx
    
## API Reference

See the [Sceneform API Reference](//developers.google.com/ar/reference/java/com/google/ar/sceneform/package-summary).

## Converter and Matc Arguments

To see the single available arguments call

```
./converter -h
```
or
```
./matc -h
```
repectively.
