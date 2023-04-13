# MeV gamma-ray source catalog

- [Table of all sources](https://tsuji703.github.io/MeV-All-Sky/files/MeV_all_source.html)
- Download:
  - Point source catalog: [csv](https://tsuji703.github.io/MeV-All-Sky/files/catalog/crossmatch_latest.csv)
  - Extended source catalog: [csv](https://tsuji703.github.io/MeV-All-Sky/files/catalog/crossmatch_latest.csv)


## What's in catalog

| Parameter | Note
| --- |---
|"Flag" | M: Matched source
|       | F: False-matched source
|       | D: Different source
|       | A: Ambiguous match
|       | U: Unidentified source
|"bat_*" | Parameters in the [Swift-BAT catalog](https://swift.gsfc.nasa.gov/results/bs105mon/)
|"fermi_*" | Parameters in the [Fermi-LAT catalog](https://fermi.gsfc.nasa.gov/ssc/data/access/lat/8yr_catalog/)
|"separation"| Angular distance between the Swift-BAT and Fermi-LAT sources in units of degree
|"Inner Gal. region" | True if the sources is located within the innter Galactic region of l<60 and b<10 degrees
|"Model" | LP (Log parabola), BPL (broken power law), 2-comp (two component model)*, or User (source-dependent model)**
| "LP_*" | Best-fit parameters with the log-parabola model. K (defined at E=1 MeV) is in units of 1/(MeV cm2 s).
| "BPL_*"| Best-fit parameters with the broken power-law model. Eb and K (at 1 MeV) are in units of eV and erg/cm2/s, respectively.

*2-comp: Two-component model. A superposition of the best-fit models in the Swift-BAT and Fermi-LAT catalogs.

**Source-dependent model: Physical model is applied based on the literature. Adopted only for sources which are not well fitted by any of models above (i.e., Circinus Galaxy, MSH 15-52, and NGC 4945).



<!--
"Flag" 
M: Matched source.
F: False-matched source.
D: Different source.
A: Ambiguous match.
U: Unidentified source.

"bat_*"
Parameters in the Swift-BAT catalog.

"fermi_*"
Parameters in the Fermi-LAT catalog.

"separation"
Angular distance between the Swift-BAT and Fermi-LAT sources in units of degree.



"Inner Gal. region" column indicates if the sources is located within the innter Galactic region of l<60 and |b|<10 degrees.

"Model" colum indicates the model used to fit the SED.

SEDs are fitted with the following models:
LP: Log parabola.
(( equation ? ))
"LP_*": best-fits parameters with the log-parabola model.

BPL: Broken power law.
"BPL_*": best-fits parameters with the broken power-law model.

2-comp: Two-component model. A superposition of the best-fit models in the Swift-BAT and Fermi-LAT catalogs.

Source-dependent model: Physical model is applied based on the literature. Adopted only for sources which are not well fitted by any of models above (i.e., Circinus Galaxy, MSH 15-52, and NGC 4945).

-->
