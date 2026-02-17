# lung-cancer-histopatholoy-dataset

The Lung Cancer Pathology Dataset is a curated collection of H&E-stained whole-slide images (WSIs) of lung tissue, obtained from the Medical Pathology Department of Kocaeli University, Faculty of Medicine.

This dataset contains histopathological lung tissue WSI images categorized into **two main classes**:

-🟥 **Cancer**
-🟩 **NonCancer**

The **Cancer** class is further divided into three subtypes of lung cancer:

  -🟦 **ADENO** – Adenocarcinoma
  -🟪 **SCC** – Squamous Cell Carcinoma
  -🟨 **NOS** – Not Otherwise Specified

The dataset is designed for deep learning and medical image analysis research.

---

▶️## Dataset Details

-🔸 **Patch format:** .tif (TIFF)  
-🔸 **Patch size:** 400×400 pixels  
-🔸 **Source:** Extracted from H&E-stained WSIs  
-🔸 **Scan magnification:** 20×  
 
---

▶️## Dataset Structure
- The dataset follows a class-wise and patient-wise hierarchical organization, as shown below:

```
dataset_root/
├── Cancer/
│   ├── ADENO/
│   │   ├── patient_001/
│   │   │   ├── patch_001.tif
│   │   │   ├── patch_002.tif
│   │   │   └── ...
│   │   ├── patient_002/
│   │   │   └── ...
│   │   └── ...
│   ├── SCC/
│   │   ├── patient_003/
│   │   │   ├── patch_001.tif
│   │   │   └── ...
│   │   ├── patient_004/
│   │   │   └── ...
│   │   └── ...
│   └── NOS/
│       ├── patient_005/
│       │   └── ...
│       ├── patient_006/
│       │   └── ...
│       └── ...
└── NonCancer/
    ├── patient_007/
    │   └── ...
    ├── patient_008/
    │   └── ...
    └── ...
```

---

▶️## Dataset Access

➡️You can download example data [here](#) (coming soon).

➡️You can download the full dataset [here](#) (coming soon).

---

▶️## Acknowledgements
Prepared in collaboration with the Medical Pathology Department of the Faculty of Medicine and the Department of Electronics and Communication Engineering of the Faculty of Engineering, Kocaeli University.
