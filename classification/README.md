![GitHub Logo](images/1.webp)





# Wine type classification

In this note, we train a classification model to analyze the chemical and visual features of wine samples and classify them based on their cultivar (grape variety).

## Citation

If you use the dataset provided in this project, please cite the original source:
**Citation**: https://archive.ics.uci.edu/dataset/109/wine

## Table of Contents

- [Classification Models](#classification-models)
- [Features](#features)
- [Installation](#installation)


## Classification Models

In this project, we have employed prominent classification models for the task of categorizing wines into distinct varieties based on their characteristics. The models used are Support Vector Machines (SVM) and Random Forest and TBA.

### Support Vector Machines (SVM)

In the context of this project, SVM has been utilized to classify wines into one of the three categories based on the provided features.

- **Accuracy on Test Set:** 0.9629629629629629
- **Precision on Test Set:** 0.9642857142857143

### Random Forest

In our project, Random Forest has been employed to predict the wine variety based on the specified features.

- **Accuracy on Test Set:** 0.9629629629629629

## Features

The wine dataset includes several features that describe various characteristics of different wines. Each sample in the dataset is labeled with a wine category, which can take one of the three values: 0, 1, or 2 standing for: 

- **0** (*Variety A*): Description of Variety A wines.

- **1** (*Variety B*): Description of Variety B wines.

- **2** (*Variety C*): Description of Variety C wines.

Also a brief explanation of some of the key features:

1. **Alcohol**: The alcohol content of the wine, measured in percentage.

2. **Malic_acid**: The amount of malic acid in the wine, which can influence its taste.

3. **Ash**: The amount of ash present in the wine, a measure of mineral content.

4. **Alcalinity**: The alkalinity of the ash in the wine, which can affect its acidity.

5. **Magnesium**: The concentration of magnesium in the wine.

6. **Phenols**: The total amount of phenolic compounds in the wine, contributing to its flavor.

7. **Flavanoids**: The amount of flavonoids in the wine, responsible for its color and taste.

8. **Nonflavanoid Phenols**: The amount of non-flavonoid phenolic compounds in the wine.

9. **Proanthocyanins**: The concentration of proanthocyanins, which are antioxidants.

10. **Color_intensity**: The intensity of the color of the wine.

11. **Hue**: The hue or color shade of the wine.

12. **OD280_315_of_diluted_wines**: The ratio of optical density at 280nm and 315nm, providing information about the color.

13. **Proline**: The amount of proline, an amino acid, in the wine.

These features collectively contribute to the classification of wines into one of the three categories: Variety A, Variety B, or Variety C.


## Installation

TBA
