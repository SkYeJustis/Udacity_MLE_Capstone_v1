# Utilizing Deep Learning on Chest X – Rays to Detect Pneumonia

## Dataset
* Data source: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
    * Download size: 1 gb
* Dataset used:
    * chest_xray_mini
        * train:
            * NORMAL: Reduced due to limited compute resource
                * Randomly selected 500 images
            * PNEUMONIA: Reduced due to limited compute resource
                * Randomly selected 500 images
        * test: All data used
        * val: All data used
        
        
## Setup via CLI
1. Have Anaconda installed. Create new conda env: conda create --name pytorch_env python=3.7
2. Activate the conda environment and install the following packages via conda install...:
    * torch
    * torchvision=0.4.2
    * PIL
    * matplotlib
    * numpy
    * cv2
    * jupyterlab
3. Once all packages are installed, type in cli `jupyter lab`
4. Run the `Data_Exploration.ipynb` and `Data_Preprocessing_Training_Refinement_And_Validation.ipynb` ipynb files
    * Depends on having the chest_xray_mini data set up in the appropriate directories relative to the ipynb files
