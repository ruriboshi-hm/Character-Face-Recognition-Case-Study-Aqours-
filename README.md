# Character-Face-Recognition（Case-Study-Aqours）

## Overview
This is character face recognition using transfer learning with VGG16. 
As a case study, I tried to recognize the faces of Aqours characters.　

## Requirement
- Google Colab
- Python 3.12.12
- TensorFlow 2.19.0

## Features
1. Detect and crop face regions from the training images using lbpcascade_animeface.
2. Split the dataset into training and test sets.
3. Build and train a CNN model using VGG16 for transfer learning.
4. Save the trained model.
5. Evaluate the model using the test dataset.

## Reference
[lbpcascade_animeface](https://github.com/nagadomi/lbpcascade_animeface?tab=readme-ov-file)

## Author
[Blog](https://ruriboshi-app.com/)
[Qiita](https://qiita.com/ruriboshi)
