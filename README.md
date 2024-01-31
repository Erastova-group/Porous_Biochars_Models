# Biochar Molecular Models with Microporocity

By Audrey Ngambia (a.l.noumbissi-ngambia@sms.ed.ac.uk) and Valentina Erastova (valentina.erastova@ed.ac.uk)

University of Edinburgh


**Please cite as**: 

A.L.N. Ngambia, O. Masek, V. Erastova, _Development of biochar molecular models with controlled porosity._ [https://doi.org/10.48550/....](https://doi.org/10.48550/....)

---

Molecular models of porous woody biochars produced at 600ºC - 650ºC highest treatment temperatures.

`Model_BCMA` - BCMA model, using uniform sizes of building blocks 

`Model_BCMB` - BCMB model, using two types of building blocks with different sizes

`Model_BCMA_V10` - BCMA model simulated with virtual atom V10-6

`Model_BCMA_V30` - BCMA model simulated with virtual atom V30-6

`Model_BCMB_V10` - BCMB model simulated with virtual atom V10-6

`Model_BCMB_V30` - BCMB model simulated with virtual atom V30-6


The folders contain all files necessary for simulation with GROMACS:
 - `.gro` files for bulk system
 - `.gro` files for surface-exposed systems
 - `.top` files assigning forcefield parameters for each structure
 -  in the cases of systems set up virtual atoms, `.gro` and `.top` for the systems with virtual atoms is also given

`oplsaa.ff` - OPLS-AA force field, as used in our simulations.

![](./figs/Fig7.png)

----

The schematic of the set-up of the biochar models:

![](./figs/Schema1.png)

For more information on the set-up of biochars, including the experimental data and molecular building blocks, please see: [github.com/Erastova-group/Biochar_MolecularModels](https://github.com/Erastova-group/Biochar_MolecularModels)

---

For more information on the set-up of biochar molecular models, please see the following publications.

- R. Wood, O. Masek, V. Erastova, _Biochars at the molecular level. Part 1 -- Insights into the molecular structures within biochars._ [https://doi.org/10.48550/arXiv.2303.09661](https://doi.org/10.48550/arXiv.2303.09661)

- R. Wood, O. Masek, V. Erastova, _Biochars at the molecular level. Part 2 -- Development of realistic molecular models of biochars._ [https://doi.org/10.48550/arXiv.2303.09907](https://doi.org/10.48550/arXiv.2303.09907)

- A.L.N. Ngambia, O. Masek, V. Erastova, _Development of biochar molecular models with controlled porosity._ [https://doi.org/10.48550/....](https://doi.org/10.48550/....)







