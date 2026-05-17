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
- You do not need to specifically rerun any code blocks because the notebook should already have all the updated plots, just add the text block explanations under each plot
- Check ALL the explanations in the registration_project notebook make sense, for all the questions

Chaymae:
- Check the rubric and the existing report template
- Write the Introduction, Study Design and Methods section (you can ask in the GC if something is not clear) 


### REQUIREMENTS

Put these commands in your anaconda prompt to download the packages we need (we now need cv2)

```
conda activate 8be030 					    # activate your environment using whatever name you called it 
pip install -r requirements.txt     # install the required packages
```

### REPO STRUCTURE

8BE030
.
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
| |____...
|____README.md
|____requirements.txt
