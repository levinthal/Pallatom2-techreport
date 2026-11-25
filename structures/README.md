# Predicted structures and metrics

This directory contains predicted complexes, binder monomers, and scoring metrics for 234
Pallatom2 minibinder designs across eight targets. The cohort includes 177
designs that expressed and 57 that did not. BCMA, IL-7RA, and reference
controls are excluded. Folder names follow the paper's target names, with
`TNFalpha` used as the directory name for TNF alpha.

Each target directory contains files named by the paper's design ID:

| File | Contents |
| --- | --- |
| `<ID>_model.cif` | Predicted target–binder complex in mmCIF format. |
| `<ID>_monomer.cif` | Independently predicted AF3 binder monomer in mmCIF format. |
| `<ID>_metrics.json` | Native AF3 summary metrics for 227 designs. For the other seven, this file contains the recorded report metrics and the mean C-alpha pLDDT calculated from the included structure. |

Each CIF starts with a comment giving the paper design ID, target, and
structure type. The data block name and entry ID match the file stem.
Original AF3 source notices, coordinates, and confidence data are retained.

The native AF3 summary metrics correspond to the included model.
The complexes for PB-009, PB-010, and PB-121 are from the local AF3
benchmark runs. The two PD-L1 complexes use a 116-residue target chain.

For the seven designs with report metrics, `recorded_metrics` transcribes
the reported values and may refer to a different scored model.
`structure_derived` describes the included coordinates.
