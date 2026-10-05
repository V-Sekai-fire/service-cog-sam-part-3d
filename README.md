# service-cog-sam-part-3d

A `cog` predictor that builds the SAMPart3D part-segmentation stack and renders a mesh's views for it.

## What it is for

The container clones SAMPart3D and builds its GPU extensions. The predictor takes a mesh and returns a directory of rendered views, the input the segmentation stage reads.

## Build and run

```sh
cog predict -i mesh_path=@thirdparty/jacket.glb
```

`setup.sh` installs the same stack into a local Linux environment.

## Licence

MIT; see `LICENSE`.
