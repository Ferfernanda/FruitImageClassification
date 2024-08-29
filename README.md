# FruitImageClassification
 
# Proyek Klasifikasi Gambar: [Fruit classification(10 Class)](https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class)

This project demonstrates a CNN model for 10 fruits classification using MobileNetV2 for Dicoding "Pengembangan Machine Learning" Final Submission.

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Dataset
This dataset project collected from Kaggle [Fruit classification(10 Class)](https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class)

Contains 3326 images of 10 fruit classification which are 'apple', 'avocado', 'banana', 'cherry', 'kiwi', 'mango', 'orange', 'pinenapple', 'watermelon', 'strawberries'
Dataset splitted by 80% Data Train, 20% Data Test

## File Structure
FruitImageClassification
├───Model
|   ├───saved_model.pb
|   ├───fingerprint.pb
|   └───variables
|       ├───variables.data-00000-of-00001
|       └───variables.index
├───tfjs_model
|   ├───group1-shard1of3.bin
|   ├───group1-shard2of3.bin
|   ├───group1-shard3of3.bin
|   └───model.json
├───tflite
|   ├───FruitClassification_MobileNetV2.tflite
|   └───label.txt
├───.gitattributes
├───README.md
├───FruitImageClassification.ipynb
└───requirements.txt
