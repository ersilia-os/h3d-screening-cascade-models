# H3D screening cascade
This repository contains data and models related to the [article](https://www.biorxiv.org/content/10.1101/2022.12.13.520154v1) _First fully-automated AI/ML virtual screening cascade implemented at a drug discovery centre in Africa_ by Turon, Hlozek, et al.

This work has been performed with [ZairaChem](https://github.com/ersilia-os/zaira-chem), an AutoML QSAR/QSPR pipeline developed by [Ersilia](https://ersilia.io).

## Download models
Models presented in the article can be downloaded as zipped files and deployed locally. For a quick exploration of these models, please visit this [online app](https://h3d-screening-cascade-app-fikzu.ondigitalocean.app).

|    | Model                       |   AUROC | Download   |
|---:|:----------------------------|--------:|:-----------|
|  0 | P. falciparum NF54 IC50     |   0.902 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/nf54_full.zip)       |
|  1 | P. falciparum K1 IC50       |   0.889 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/k1_full.zip)       |
|  2 | M. tuberculosis MIC90       |   0.903 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/mtb_full.zip)       |
|  3 | CHO IC50                    |   0.871 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/cho_full.zip)       |
|  4 | HepG2 IC50                  |   0.973 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/hepg2_full.zip)       |
|  5 | CLint Human                 |   0.816 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/clintH_full.zip)       |
|  6 | CLint Mouse                 |   0.802 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/clintM_full.zip)       |
|  7 | CLint Rat                   |   0.802 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/clintR_full.zip)       |
|  8 | Aqueous solubility (pH=7.4) |   0.893 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/sol_full.zip)       |
|  9 | Aqueous solubility (pH=6.5) |   0.884 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/sol65_full.zip)       |
| 10 | Caco-2                      |   0.941 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/caco_full.zip)       |
| 11 | CYP2C9 IC50                 |   0.803 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/sol65_full.zip)       |
| 12 | CYP2C19 IC50                |   0.618 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/cyp_all_cyp2c19.zip)       |
| 13 | CYP2D6 IC50                 |   0.666 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/cyp_all_cyp2c9.zip)       |
| 14 | CYP3A4 IC50                 |   0.793 | [link](https://zairachem-models.s3.eu-central-1.amazonaws.com/h3d_screening_cascade_anonymised/cyp_all_cyp2d6.zip)       |
| 15 | hERG IC50                   |   0.852 | link       |


