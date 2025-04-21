# TurbineGov Study

## ACTIVSg200

``IL200_opf.xlsx`` and ``IL200_dyn.xlsx`` are revised from below reference.

Illinois 200-Bus System: ACTIVSg200

URL: <https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg200/>

References:

## ACTIVSg2000

``texas2k.xlsx`` is revised from below reference.

References:
1. W. Wang, X. Fang, H. Cui, F. Li, Y. Liu and T. J. Overbye, “Transmission-and-Distribution
   Dynamic Co-Simulation Framework for Distributed Energy Resource Frequency Response,” in
   IEEE Transactions on Smart Grid, vol. 13, no. 1, pp. 482-495, Jan. 2022,
   doi: 10.1109/TSG.2021.3118292.

## Texas2k Series24 Cases with Improved Dynamics

The test case is revised from Texas2k Series24 Cases with Improved Dynamics.
Case 5: 2024 High Renewables (high penetration of renewables case for 2024)
URL: <https://electricgrids.engr.tamu.edu/activsg2000-dynamics-cases-2024/>

- ``Texas2k_case5.m`` is renamed from ``Texas2k_series24_case5_2024highrenewables.m``
- ``Texas2k.dyr`` and ``Texas2k.raw`` are renamed from dynamic_models_case5.dyr and
  ``Texas2k_series24_case5_2024highrenewables.RAW``, respectively.
- ``Texas2k_v33.raw`` is converted from ``Texas2k.raw`` using PSSE.
- ``Texas2k_case5_mod.dyr`` is modified from ``Texas2k.dyr`` to replace some unsupported
  models with supported models in ANDES. However, this case fails to initialize
  TDS, and thus is not used in this study.

References:
1. A.B. Birchfield, T. Xu, K.M. Gegner, K.S. Shetye, and T.J. Overbye, “Grid Structural
   Characteristics as Validation Criteria for Synthetic Networks,” IEEE Transactions on
   Power Systems, vol. 32, no. 4, pp. 3258-3265, July 2017.
1. J. Baek and A. B. Birchfield, “A tuning method for exciters and governors in realistic
   synthetic grids with dynamics,” 2023 North American Power Symposium (NAPS), Asheville,
   NC, USA, Oct. 2023, pp. 1-6.
