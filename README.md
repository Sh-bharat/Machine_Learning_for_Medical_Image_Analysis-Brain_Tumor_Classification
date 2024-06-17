---

# Machine_Learning_for_Medical_Image_Analysis-Brain_Tumor_Classification

## Overview
This project focuses on classifying brain tumor MRI images into 44 different classes using YOLOv8, a state-of-the-art object detection algorithm. The dataset used for training and evaluation is sourced from Kaggle and consists of MRI images with various types of brain tumors.

## Dataset
- **Source:** [Brain Tumor MRI Images](https://www.kaggle.com/datasets/fernando2rad/brain-tumor-mri-images-44c)
- **Total Images:** 44 classes with varying image counts (ranging from 31 to 43 images per class)
  
### Classes
1. Neurocitoma T1C+
2. Meduloblastoma T1C+
3. Ependimoma T2
4. Astrocitoma T1
5. _NORMAL T2
6. Ganglioglioma T2
7. Granuloma T1
8. Carcinoma T1C+
9. Neurocitoma T2
10. Papiloma T1
11. Tuberculoma T1C+
12. Glioblastoma T2
13. Carcinoma T2
14. Meningioma T1C+
15. Papiloma T2
16. Oligodendroglioma T1
17. Granuloma T2
18. Schwannoma T1
19. Astrocitoma T1C+
20. Meduloblastoma T1
21. Germinoma T2
22. Papiloma T1C+
23. Glioblastoma T1C+
24. Ependimoma T1C+
25. Oligodendroglioma T2
26. Carcinoma T1
27. Ependimoma T1
28. Neurocitoma T1
29. Schwannoma T2
30. Astrocitoma T2
31. Ganglioglioma T1C+
32. Glioblastoma T1
33. Schwannoma T1C+
34. Ganglioglioma T1
35. Germinoma T1C+
36. Meduloblastoma T2
37. Tuberculoma T1
38. Germinoma T1
39. Oligodendroglioma T1C+
40. _NORMAL T1
41. Tuberculoma T2
42. Granuloma T1C+
43. Meningioma T2
44. Meningioma T1

## Sample Predicted Image
![val_batch2_pred](https://github.com/Sh-bharat/Machine_Learning_for_Medical_Image_Analysis-Brain_Tumor_Classification/assets/133742551/96bb145f-7a0f-4f31-bc92-bee38476851d)


## Model Performance
- **Accuracy:** 97%

##  Result 
<img src="https://github.com/Sh-bharat/Machine_Learning_for_Medical_Image_Analysis-Brain_Tumor_Classification/assets/133742551/71988f44-3e82-4a99-b721-7057cc5814b5" width='700'>


## Usage
1. **Training:** Use the provided dataset to train the YOLOv8 model.
2. **Inference:** Once trained, the model can be used to classify brain tumor MRI images. Provide an image to the model, and it will predict the class of the brain tumor present.

Got it! Here's the updated section:


## Libraries Required
```python
import zipfile
import os
import shutil
from tqdm import tqdm
import cv2
import matplotlib.pyplot as plt
from ultralytics import YOLO
```
## Credits

Created by Bharat_Sharma<br>
for any suggestion, Queries feel free to contact bharat05122002@gmail.com

---
