# Food101 EfficientNetV2 Fine-Tuning

This repository contains code for fine-tuning the EfficientNetV2B0 model on the Food101 dataset for image classification. The project focuses on transfer learning to achieve high accuracy in recognizing food categories. Its purpose is to demonstrate that modern lightweight models can outperform the larger models used in research from 2016 (as seen in the original Food101 study).

In the main notebook, `FoodVisionProject.ipynb`, I achieved a **top-1 accuracy of nearly 80%** with significantly less training time and computational resources compared to the baseline research on Food101. As well as suggested a direction for improvements.

## Features

* Fine-tuning of EfficientNetV2 on Food101 dataset
* Data preprocessing and augmentation pipeline designed according to the best practices
* Training and validation scripts with different model callbacks
* Techniques to optimize the training process (mixed-precision, effective data preprocessing pipelines)
* Simple and clear implementation for transfer learning experiments

## Project Stack

|     Layer     |         Technology / Library        |
| :------------------------: | :---------------------------------------------: |
|       **Framework**        |                    Tensorflow                   |
|          **Data**          |                  Food101 dataset                |
|         **Model**          |       EfficientNetV2B0 (pretrained weights)     |

## License

MIT License

---
