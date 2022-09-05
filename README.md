# Soil-erosion-detection
Soil erosion detection - Quantum Task

## 1. Preprocessing and Analysis
In this section we, by using file [Preprocessing.ipynb](https://github.com/Diana-Kapralova/Soil-erosion-detection/blob/main/Preprocessing.ipynb), make analysis and preproc data
## 2. Modeling
In this section we, by using file [Modeling.ipynb](https://github.com/Diana-Kapralova/Soil-erosion-detection/blob/main/Modeling.ipynb) make a U-Net model for prediction soil erosion with given satellite image.
## HOW IT WORKS
1. Original Image: not saved here because of large size, but should be added to folder [original](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/original) 
2. Preprocessing.ipynb: preproc data and created mask from shape file in folder [mask](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/masks) and saved in [original](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/original) named label.jp2) 
3. Modeling: here use all files(image mask implementation and Original Image) for modeling. As result: model.
