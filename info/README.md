## Model grid reference

- **EPSG:** 2193 (NZGD2000 / NZTM)
- **Grid:** 302 rows × 501 columns × 2 layers
- **Cell size:** 100m × 100m
- **Lower left corner (origin):** E 1,891,460 m, N 5,594,400 m
- **Upper right corner:** E 1,941,560 m, N 5,624,600 m

## Files

### Bore locs

- **bore_coordinates.txt** - Tab-delimited text: BoreID, Easting, Northing, Layer (478 bores)
- **borecoord_e.dat** - Text format (subset of bores)
- **borecoord_tr.dat** - Text format (subset of bores)

### Zone Definitions for Post-Processing Model Results

- **tabl4.dat** - Zone definition file (302×501 grid of MODFLOW zone IDs)
- **source_modflow_zones4.csv** - Lookup table mapping MODFLOW zone IDs to SOURCE_IDs and stream groups (Raupare, Ngaruroro, Karamu, Mangateretere, Tutaekuri-Waimate, Tutaekuri, Tukituki, Irongate, Karewarewa, etc.)

**Note:** `tabl4.dat` and `source_modflow_zones4.csv` work together to extract and aggregate model results by stream catchment zones.
