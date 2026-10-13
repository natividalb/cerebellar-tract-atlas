# Cerebellar Tract Atlas (MNI space)

This repository contains a white-matter tractography atlas of cerebellar
pathways, built from a population of 30 subjects and registered to MNI
standard space. It is provided to accompany an associated publication.

## Contents

```
Atlas_tck_MNI/            Full-resolution streamlines, MRtrix .tck format
Atlas_bundles_MNI/        Full-resolution streamlines, BrainVISA/Connectomist .bundles/.bundlesdata format
Atlas_bundles_MNI_21p/    Same bundles resampled to 21 points per streamline (.bundles/.bundlesdata)
atlas_CBLO_MNI_21p.hie    Hierarchy/color file for visualization (Anatomist/BrainVISA)
radios_cblo.txt           Per-bundle streamline counts / radii used to build the atlas
```

Each bundle is provided per hemisphere where applicable (`_L` / `_R` suffix)
and named `<BUNDLE>_all30_MNI[.ext]` or `<BUNDLE>_all30_MNI_21p[.ext]`,
reflecting that it was built from all 30 subjects in MNI space.

### Bundles included

| Abbreviation | Hemispheres |
|---|---|
| CPH  | L, R |
| CTC  | L, R |
| DRTC | L, R |
| FPC  | L, R |
| ICP  | L, R |
| MCP  | — (single bundle) |
| OPC  | L, R |
| OVC  | — (single bundle) |
| PAG  | — (single bundle) |
| PPC  | L, R |
| SCP  | — (single bundle) |
| SPNC | L, R |


## Usage

These data represent group-level (atlas) bundles already registered to MNI
space; no further registration is required to overlay them on an MNI
template.

## Citation

If you use this atlas, please cite the associated publication:

> _Add citation here once published._

## License

_To be defined._
