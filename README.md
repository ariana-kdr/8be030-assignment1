# 8be030-assignment1
8be030 - medical imaging analysis repo for assignment 1 (registration) 

TODOS 17-05-2026

Ariana:
- Make Gaussian noise function -> DONE
- Clean up existing code -> DONE
- Make repo -> DONE

Cecilia:
- Which photos to use? Make clear set
- Choose which Gaussian standard deviation parameters to use
- You can use the registration_project notebook for this as it has a code block at the end to test the Gausian function. You don't need to rerun the whole notebook, just the two blocks at the top that import all the packages 
- Make a plan for who looks at which photos, which similarity measures and which st devs

Yousra:
- Move explanations in colab notebook to this repo and push the updated file
- You might have to change some explanations because we made some changes to the code during last week's meeting 
- Check ALL the explanations in the registration_project notebook make sense, for all the questions

Chaymae:
- Check the rubric and the existing report template
- Write the Introduction, Study Design and Methods section (you can ask in the GC if something is not clear) 


### IMPORTANT FOR RUNNING THE NOTEBOOK
**Install all requirements**
Run these commands in your anaconda prompt to download the packages we need BEFORE you try running Registration_project.ipnyb
```
conda activate 8be030 					    # activate your environment using whatever name you called it 
pip install -r requirements.txt     # install the required packages
```
**Importing packages**
Run these blocks at the top of 1.6_Registration_project.ipnyb so you don't need to run any other blocks throughout the notebook for importing stuff. 
```
%load_ext autoreload
%autoreload 2
```
```
import sys
import numpy as np
from scipy import ndimage
import matplotlib.pyplot as plt
import cv2 

sys.path.append("../code")
import registration as reg
import registration_util as util
from registration_project import intensity_based_registration_demo
from registration_project import intensity_based_registration
from registration_project import get_params
from registration_project import gaussian_noise
```

### REPO STRUCTURE

```
|____code
| |____registration.py
| |____registration_tests.py
| |____registration_util.py
| |____registration_project.py
| |____...
|____data
|____reader
| |____0.1_Software_guide.ipynb
| |____1.1_Geometrical_transformations.ipynb
| |____1.2_Point-based_registration.ipynb
| |____1.4_Intensity-based_registration.ipnyb
| |____1.5_Validation_in_medical_image_analysis_part_1.ipnyb
| |____1.6_Registration_project.ipnyb
|____README.md
|____requirements.txt
```
