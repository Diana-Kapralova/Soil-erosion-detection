# Soil-erosion-detection
Soil erosion detection - Quantum Task

Here is one of the open problems in Quantum. Soil erosion is a really unwanted process that spoils huge areas of fertile land. Your task is to train model for erosion detection.

**What do you have**
* Sentinel2 tile (T36UXV_20200406T083559_TCI_10m.jp2);
* Masks with soil erosion for this tile (masks directory);

**What should we get**

As usual it should be github repository that contains:
* jupyter notebook with data analysis;
* script for model training (preferably tf.keras);
* readme file;
* requirements.txt file;
* **solution report**. This is the most important part. We expect here not only solution description but also your proposals and result of research in different papers about soil erosion detection problem. In other words - what can help us to solve problem in the most effective way.

## 1. Preprocessing and Analysis
In this section we, by using file [Preprocessing.ipynb](https://github.com/Diana-Kapralova/Soil-erosion-detection/blob/main/Preprocessing.ipynb), make analysis and preproc data
## 2. Modeling
In this section we, by using file [Modeling.ipynb](https://github.com/Diana-Kapralova/Soil-erosion-detection/blob/main/Modeling.ipynb) make a U-Net model for prediction soil erosion with given satellite image.
## HOW IT WORKS
1. Original Image: not saved here because of large size, but should be added to folder [original](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/original) 
2. Preprocessing.ipynb: preproc data and created mask from shape file in folder [mask](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/masks) and saved in [original](https://github.com/Diana-Kapralova/Soil-erosion-detection/tree/main/original) named label.jp2) 
3. Modeling: here use all files(image mask implementation and Original Image) for modeling. As result: model.

## Solution Report
Report created in pdf file named [Improving_for_Model.pdf](https://github.com/Diana-Kapralova/Soil-erosion-detection/blob/main/Improving_for_Model.pdf)



