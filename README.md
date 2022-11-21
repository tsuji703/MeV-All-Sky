Materials in the MeV gamma-ray sky, source catalog and all-sky maps, are available below.
The source catalog is produced by a cross-matching of the hard X-ray (by Swift-BAT) and GeV gamma-ray (Fermi-LAT) catalogs.
The all-sky maps made use of [GALPROP](https://galprop.stanford.edu/) for Galactic diffuse emission, the source catalog, and cosmic gamma-ray background (CGB) model by COMPTEL.


# MeV Gamma-ray Source Catalog

This catalog is based on <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ac0341">Tsuji et al. 2021</a>
(cross-match between the <a href="https://swift.gsfc.nasa.gov/results/bs105mon/">105-month Swift-BAT</a>
and <a href="https://fermi.gsfc.nasa.gov/ssc/data/access/lat/8yr_catalog/">Fermi-LAT</a> catalogs).


### Latest
- [Table of all sources](https://tsuji703.github.io/MeV-All-Sky/files/MeV_all_source.html)
- Point source catalog: [fits](files/catalog/crossmatch_latest.fits), [csv](files/catalog/crossmatch_latest.csv)
- Extended source catalog: [fits](files/catalog/crossmatch_latest_extended.fits), [csv](files/catalog/crossmatch_latest_extended.csv)

<!--
- ver. 1
  - Shown with Log-parabola fit
  - [Point source](https://github.com/tsuji703/MeV-All-Sky/blob/main/files/MeV_point_source_LogParabola.md)
  - [Extended source](https://github.com/tsuji703/MeV-All-Sky/blob/main/files/MeV_extended_source_LogParabola.md)

- ver. 0
  - BPL fitting
  - [Point source](https://github.com/tsuji703/MeV-All-Sky/blob/main/files/MeV_point_source.md)
  - [Extended source](https://github.com/tsuji703/MeV-All-Sky/blob/main/files/MeV_extended_source.md)
-->

# MeV Gamma-ray All-Sky Map


- FITS file: [Allsky-fits-Model1](files/allsky/data_allsky_total.fits) (Model 1 for GDE)


## 1. Galactic Diffuse Emission

| Model | Notes | Galdef file | FITS fils |
|---|---|---|---|
| 1 | [Ackermann et al. 2012](https://iopscience.iop.org/article/10.1088/0004-637X/750/1/3). `SS_Z4_R20_T150_C54` model in Ackermann et al. 2012. | [galdef-1](files/allsky/galdef_54_0abb001h) | [GDE-fits-Model1](files/allsky/data_allsky_galactic_Ackermann.fits)
| 2 | [Olrando 2018; DRE model](http://doi.org/10.1093/mnras/stx3280) | [galdef-2](files/allsky/galdef_54_0abb001j) |
| 3 | [Olrando 2018; DRELowV model](http://doi.org/10.1093/mnras/stx3280) | [galdef-3](files/allsky/galdef_54_0abb001i) | 


## 2. MeV Gamma-ray Source

- FITS file: [Source-fits](files/allsky/data_allsky_source.fits)

![MeV gamma-ray source map](files/allsky/figure_allsky_source_2.pdf)



## 3. Extragalactic Emission (Cosmic Gamma-ray Background)

- FITS file: [CGB-fits](files/allsky/data_cgb_source.fits)


---
Please contact <ntsuji [at] kanagawa-u.ac.jp> about this page.

