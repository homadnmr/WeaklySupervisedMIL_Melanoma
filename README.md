# (Weakly supervised deep learning image analysis can differentiate melanoma from naevi on haematoxylin and eosin-stained histopathology slides)
We followed the CLAM model prepreationa nd preprocessing steps.
Training
====
For training, refer to the three Multi-Instance Learning (MIL) models:
1.Clustering-constrained Attention Multiple Instance Learning (CLAM): (https://github.com/mahmoodlab/CLAM/tree/master).
2.DTFD-MIL: Double-Tier Feature Distillation Multiple Instance Learning for Histopathology Whole Slide Image Classification: (https://github.com/hrzhang1123/DTFD-MIL/tree/main).
3.TransMIL: Transformer based Correlated Multiple Instance Learning for Whole Slide Image Classification: (https://github.com/szc19990412/TransMIL/tree/main)

Dataset:
====
For training,validation and test purposes we used our private dataset.

Trained Packages
====
We have provided trained models (checkpoints) for all three MIL frameworks, using three magnifications (10x, 20x, and 40x) and employing 5-fold cross-validation

| method | url |
|-------------------|---------------------------------------|
| CLAM  | [model](https://drive.google.com/file/d/11xwankCL-vCYEC4xrhIP5YZtMRPSqJhK/view?usp=drive_link) |
| TransMIL|  [model](https://drive.google.com/file/d/1xGhTiw0wZD5t08SstjrJbvRJU2jhA-bQ/view?usp=drive_link) | 
| DTFD-MIL|  [model](https://drive.google.com/file/d/1GQjKblX3OaNQSlVMCtaLliVhRpVO4Zif/view?usp=drive_link) |
 
