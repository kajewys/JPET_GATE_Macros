# JPET_GATE_Macros

J-PET scanner prototypes for GATE simulations. Basic geometry: 50cm EJ230 plastic scintillators, 85cm diameter, 20 modules with two layers of 14 scintillators each.
Perpendicular WLS blocks are added to help locate the initial Compton interaction location and are marked green in geometry.

# NOTES:

The CASToR reconstruction folder has two major changes: crystal arrays and removal of WLS blocks.
Each scintillator was subdivided into 100 crystal blocks strictly for CASToR reconstruction purposes and does not reflect actual design.
WLS blocks were excluded because they were being misinterpreted by CASToR during geometry detection stage.

The total-body folder has same basic geometry as the 1-ring version. There are three 50cm rings with 5cm spacing - 160cm total length. WLS are included.

A big thank you goes to Jakub Baran for helping me with the simulations and setting up reconstruction.
