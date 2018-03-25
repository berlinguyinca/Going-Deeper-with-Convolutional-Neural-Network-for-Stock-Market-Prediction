# Going Deeper with Convolutional Neural Network for Stock Market Prediction
Repository for Going Deeper with Convolutional Neural Network for Stock Market Prediction

## Introduction
Predict the stock market price will go up or not in the near future.

## Data Collection
- Using Yahoo! Finance for time series data source
- EWT and FtW are Taiwan Stock Market
- IDX and EIDO are Indonesia Stock Market

## Methodology
- CNN with Residual Network architecture.
- ResNet50, ResNet101, ResNet152, ResNet182

## Performance Evaluation
- Accuracy
- Specitivity
- Sensitivity
- MCC
- F1

## Result
20 period days using ResNet50
| 20-res50 | TN | FN |  TP | FP |      TPR     |      FPR      |   Acc  |   Spe  |  Sens  |   MCC  |   F1   |
|:--------:|:--:|:--:|:---:|:--:|:------------:|:-------------:|:------:|:------:|:------:|:------:|:------:|
| EWT      | 77 | 12 | 186 | 8  | 0.9393939394 | 0.09411764706 | 92.90% | 90.60% | 93.90% | 83.50% | 93.00% |
| EIDO     | 72 | 34 | 151 | 26 | 0.8162162162 | 0.2653061224  | 78.80% | 73.50% | 81.60% | 54.20% | 79.00% |
| FTW      | 83 | 20 | 157 | 23 | 0.8870056497 | 0.2169811321  | 84.80% | 78.30% | 88.70% | 67.40% | 85.00% |
| IDX      | 73 | 30 | 159 | 21 | 0.8412698413 | 0.2234042553  | 82.00% | 77.70% | 84.10% | 60.50% | 82.00% |

10 period days using ResNet50
| 10-res50 |  TN | FN |  TP | FP |      TPR     |      FPR     |   Acc  |   Spe  |  Sens  |   MCC  |   F1   |
|:--------:|:---:|:--:|:---:|:--:|:------------:|:------------:|:------:|:------:|:------:|:------:|:------:|
| EWT      | 96  | 12 | 170 | 15 | 0.9340659341 | 0.1351351351 | 90.80% | 86.50% | 93.40% | 80.30% | 91.00% |
| EIDO     | 98  | 25 | 142 | 28 | 0.8502994012 | 0.2222222222 | 81.90% | 77.80% | 85.00% | 63.00% | 82.00% |
| FTW      | 108 | 23 | 148 | 14 | 0.865497076  | 0.1147540984 | 87.40% | 88.50% | 86.50% | 74.40% | 87.00% |
| IDX      | 97  | 23 | 149 | 24 | 0.8662790698 | 0.1983471074 | 84.00% | 80.20% | 86.60% | 66.90% | 84.00% |

5 period days using ResNet50
| 5-res50 |  TN | FN |  TP | FP |      TPR     |      FPR     |   Acc  |   Spe  |  Sens  |   MCC  |   F1   |
|:-------:|:---:|:--:|:---:|:--:|:------------:|:------------:|:------:|:------:|:------:|:------:|:------:|
| EWT     | 99  | 29 | 146 | 24 | 0.8342857143 | 0.1951219512 | 82.20% | 80.50% | 83.40% | 63.60% | 82.00% |
| EIDO    | 113 | 29 | 131 | 25 | 0.81875      | 0.1811594203 | 81.90% | 81.90% | 81.90% | 63.70% | 82.00% |
| FTW     | 125 | 22 | 132 | 19 | 0.8571428571 | 0.1319444444 | 86.20% | 86.80% | 85.70% | 72.50% | 86.00% |
| IDX     | 114 | 24 | 129 | 31 | 0.8431372549 | 0.2137931034 | 81.50% | 78.60% | 84.30% | 63.10% | 82.00% |
