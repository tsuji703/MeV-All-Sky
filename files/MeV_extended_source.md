## Extended source
- 31 extended sources, which have more than one Swift-BAT sources in the Fermi-LAT extent.
- BPL fitting
  - crossmatch_latest_extended_BPLfit.csv
  - Used the nearest or associated BAT spectrum in the hard X-ray range.
  - Index1 is fixed to BAT.
  - Using Sherpa for fitting.


| id| Flag| fermi_coord| fermi_extended_model_major| fermi_pindex_PL| fermi_flux| bat_name_counterpart_nearest| bat_category_type_nearest| sep_nearest| bat_pindex_nearest| bat_flux_nearest| bat_name_counterpart| bat_category_type| SED&nbsp;&nbsp;&nbsp;&nbsp;option&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;option&nbsp;&nbsp;&nbsp;&nbsp;;&nbsp;&nbsp;&nbsp;&nbsp;option&nbsp;&nbsp;&nbsp;&nbsp;
|--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |---
| 1 | F | (80, -68.75) | 3.0 | 2.19 | 11 | 2MASX J05052442-6734358 | Unknown AGN | 1.7 | 2.02 | 1 | SWIFT J045106.8-694803; IGR J05007-7047; 2MASX J05052442-6734358; LMC X-4; RX J0531.2-6609; LMC X-1; PSR B0540-69; XMMU J054134.7-682550; [RSG2010] A;  | HMXB; HMXB; Unknown AGN; HMXB; HMXB; HMXB; Pulsar; HMXB; HMXB;  | ![](figures/SED_sherpa/Extended_BPL_LMC-Galaxy.png)
| 2 | F | (75.25, -69.75) | 0.9 | 2.1 | 2 | SWIFT J045106.8-694803 | HMXB | 0.8 | 2.48 | 3.3 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_LMC-FarWest.png)
| 3 | F | (82.5, -69) | 0.9 | 2.12 | 4.4 | RSG2010 A | HMXB | 1.0 | 2.82 | 0.57 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_LMC-30DorWest.png)
| 4 | F | (82.97, -66.65) | 0.6 | 2.0 | 2.3 | LMC X-4 | HMXB | 0.3 | 2.83 | 33 | LMC X-4; RX J0531.2-6609;  | HMXB; HMXB;  | ![](figures/SED_sherpa/Extended_BPL_LMC-North.png)
| 5 | F | (14.5, -72.75) | 1.5 | 2.2 | 2.5 | IGR J01054-7253 | HMXB | 0.3 | 3.46 | 0.34 | RX J0052.1-7319; RX J0053.8-7226; IGR J01054-7253; XTE J0103-728; SXP 202;  | HMXB; HMXB; HMXB; HMXB; HMXB;  | ![](figures/SED_sherpa/Extended_BPL_SMC-Galaxy.png)
| 6 | M | (201, -43.5) | 2.5 | 2.51 | 5.2 | Cen A | Beamed AGN | 0.5 | 1.88 | 1.4e+02 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_CenA_Lobes.png)
| 7 | M | (128.3, -45.19) | 0.9 | 2.18 | 13 | Vela Pulsar | Pulsar | 0.4 | 1.97 | 18 | Vela Pulsar; SWIFT J0837.8-4440;  | Pulsar; U2;  | ![](figures/SED_sherpa/Extended_BPL_Vela_X.png)
| 8 | M | (215.1, -60.78) | 0.1 | 2.0 | 3.7 | Rabbit | Pulsar | 0.2 | 1.53 | 0.8 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_HESS_J1420-607.png)
| 9 | M | (228.6, -59.16) | 0.2 | 1.83 | 5.3 | PSR B1509-58 | Pulsar | 0.0 | 1.85 | 26 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_MSH_15-52.png)
| 10 | M | (244.1, -50.91) | 0.3 | 2.05 | 12 | PSR J1617-5055 | Pulsar | 0.2 | 2.05 | 1.5 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_HESS_J1616-508.png)
| 11 | M | (276.1, -13.85) | 0.8 | 1.75 | 14 | IGR J18246-1425 | Pulsar | 0.6 | 2.8 | 1.9 | IGR J18246-1425; XMMSL1 J182155.0-134719;  | Pulsar; HMXB;  | ![](figures/SED_sherpa/Extended_BPL_HESS_J1825-137.png)
| 12 | M | (280.2, -5.55) | 0.6 | 1.98 | 13 | AX J1841.0-0535 | HMXB | 0.1 | 1.91 | 2.5 | AX J1841.0-0535; 1E 1841-045;  | HMXB; Pulsar;  | ![](figures/SED_sherpa/Extended_BPL_HESS_J1841-055.png)
| 13 | M | (247.9, -47.94) | 0.3 | 1.76 | 3 | AX J1631.9-4752 | Pulsar | 0.1 | 2.84 | 31 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_FGES_J1631.6-4756.png)
| 14 | M | (279.1, -6.866) | 0.5 | 2.04 | 22 | PSR J1838-0655 | Pulsar | 0.3 | 1.71 | 6.9 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_FGES_J1836.5-0651.png)
| 15 | M | (279.7, -7.067) | 0.5 | 1.85 | 7 | PSR J1838-0655 | Pulsar | 0.3 | 1.71 | 6.9 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_FGES_J1838.9-0704.png)
| 16 | F | (66.82, 55.55) | 1.5 | 1.68 | 4.1 | XTE J0421+560 | HMXB | 1.2 | 2.27 | 1.2 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_G150.3+4.5.png)
| 17 | U | (85.1, 27.94) | 1.5 | 2.18 | 5.7 | SWIFT J053457.91+282837.9 | U2 | 1.3 | 2.35 | 1.2 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_S_147.png)
| 18 | F | (99.86, 6.93) | 3.5 | 2.3 | 9.1 | 2MASX J06262702+0727287 | Unknown AGN | 3.2 | 1.87 | 1.6 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_Monoceros.png)
| 19 | M | (133, -46.34) | 1.0 | 1.79 | 12 | PSR J0855-4644 | Pulsar | 0.8 | 2.06 | 1 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_Vela_Junior.png)
| 20 | A | (249.1, -47.52) | 0.1 | 2.34 | 10 | SGR 1627-41 | Gamma-ray source | 0.1 | 1.81 | 1.4 | SGR 1627-41; IGR J16358-4726;  | Gamma-ray source; Pulsar;  | ![](figures/SED_sherpa/Extended_BPL_G337.0-0.1.png)
| 21 | F | (305.3, 40.52) | 0.6 | 1.96 | 10 | 2MASX J20183871+4041003 | Sy2 | 0.5 | 2.03 | 2.6 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_gamma_Cygni.png)
| 22 | M | (258.4, -39.76) | 0.6 | 1.71 | 7 | SWIFT J1712.9-4002 | U1 | 0.3 | 3.25 | 1.3 | SNR G347.3-0.5; SWIFT J1712.9-4002;  | SNR; U1;  | ![](figures/SED_sherpa/Extended_BPL_RX_J1713.7-3946.png)
| 23 | F | (307.2, 41.17) | 3.0 | 2.09 | 1.2e+02 | Cyg X-3 | HMXB | 0.7 | 3.0 | 2.5e+02 | 2MASX J20183871+4041003; Cyg X-3; SSTSL2 J203705.58+415005.3;  | Sy2; HMXB; Beamed AGN;  | ![](figures/SED_sherpa/Extended_BPL_Cygnus_Cocoon.png)
| 24 | M | (248.3, -47.77) | 0.6 | 2.17 | 25 | AX J1631.9-4752 | Pulsar | 0.2 | 2.84 | 31 | AX J1631.9-4752; 4U 1630-47; IGR J16328-4726; SGR 1627-41; IGR J16358-4726;  | Pulsar; LMXB; HMXB; Gamma-ray source; Pulsar;  | ![](figures/SED_sherpa/Extended_BPL_FGES_J1633.0-4746.png)
| 25 | A | (272.6, -19.43) | 0.5 | 2.36 | 5.1 | PSR J1811-1925 | Pulsar | 0.3 | 2.07 | 3.5 | XTE J1810-189; PSR J1811-1925;  | LMXB; Pulsar;  | ![](figures/SED_sherpa/Extended_BPL_HESS_J1809-193.png)
| 26 | M | (273.3, -17.62) | 0.6 | 2.34 | 15 | IGR J18135-1751 | SNR | 0.2 | 1.92 | 4.1 | IGR J18135-1751; GX 13+1;  | SNR; LMXB;  | ![](figures/SED_sherpa/Extended_BPL_HESS_J1813-178.png)
| 27 | F | (278.6, -8.78) | 0.2 | 2.13 | 11 | Swift J1834.9-0846 | star | 0.2 | 2.13 | 0.96 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_W_41.png)
| 28 | M | (280.2, -4.89) | 0.3 | 2.37 | 7.2 | 1E 1841-045 | Pulsar | 0.1 | 1.33 | 11 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_Kes_73.png)
| 29 | U | (159.1, -58.56) | 2.5 | 1.93 | 29 | Eta Carina | XRB | 1.6 | 3.76 | 0.78 | 4U 1036-56; Eta Carina; 2MASS J10445192-6025115;  | HMXB; XRB; star;  | ![](figures/SED_sherpa/Extended_BPL_FGES_J1036.3-5833.png)
| 30 | U | (212.3, -61.35) | 0.7 | 2.16 | 25 | SWIFT J1408.2-6113 | CV | 0.2 | 2.68 | 1.2 | [CG2001] G311.45-0.13; SWIFT J1408.2-6113; MAXI J1409-619;  | U2; CV; Pulsar;  | ![](figures/SED_sherpa/Extended_BPL_FGES_J1409.1-6121.png)
| 31 | U | (272, -20.48) | 0.6 | 2.57 | 4.9 | SGR 1806-20 | Pulsar | 0.1 | 1.66 | 5.3 | ... | ... | ![](figures/SED_sherpa/Extended_BPL_HESS_J1808-204.png)

