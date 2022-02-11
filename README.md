# Dog Breed Identification System Using Deep Learning 🐕
<p align="center">
  <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">
  <img src="http://ForTheBadge.com/images/badges/built-by-developers.svg">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Last%20Commit-Feb 2022-brightgreen"> 
  <img src="https://img.shields.io/badge/Project%20Status-Open-brightgreen">
</p>

<p align='center'>
  <img src='https://www.coindesk.com/resizer/fl_rRSS54xUlJKEmpi4xAq1y0_s=/1200x600/center/top/cloudfront-us-east-1.images.arcpublishing.com/coindesk/WMXJCFJ3ERCETA6TJNZ5NQPNKA.webp' width=900>
</p>

## Table of Contents
1. Introduction :white_check_mark:
2. Environment Setup :white_check_mark:
3. Gathering The Data :white_check_mark:
4. Exploratory Data Analysis (EDA) :white_check_mark:
5. Dataset Preprocessing <br>
    5.1 Encoding Labels <br> 
    5.2 Image Preprocessing <br>
    5.3 Batching The Data <br>
6. Model Experimentation :white_check_mark: <br>
    6.1 Experiment 1 : MobileNetV2 <br>
    6.2 Experiment 2 : EfficientNetV2 <br>
    6.3 Experiment 3 : ResNet50V1 <br>
    6.4 Experiment 4 : InceptionV3 <br>
7. Model Evaluation :white_check_mark: <br>
    7.1 Evaluating Model Experimentations <br>
    7.2 Fitting Champion Model <br>
    7.3 Unbatching The Data <br>
    7.4 Evaluating The Champion Model <br>

## Results

**Note: The accuracy may vary with different runs** <br> <br>
**Experimentation Results** <br>

| Model	                    |Best Epochs | Training Accuracy (%)| Validation Accuracy (%)  |
|---	                    |---	           |---	                |--- |
| MobileNetV2 | 3 | 94.02% | 80.44% |
| EfficientNetv2 | 3 | 86.12% | 72.81% |
| ResNet50V1 | 39 | 89.18% | 87.48% |
| InceptionV3 | 7 | 97.85% | 80.54% |

<br>

**Champion Model : ResNet50V1 Results** <br>

| Metrics                    | Results (%) |
|---	                       |--- |
| Accuracy | 87.53% |
| Precision Score | 87.44% |
| Recall Score | 86.76% |
| F1 Score | 86.34% |
