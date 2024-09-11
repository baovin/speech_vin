## Dataset
CREMA-D
[Link Dataset](https://www.kaggle.com/datasets/phmvittin/cremad-1)
---
**NOTE**
---
## Pretrained Weight for Multimodal
1. [Audio_Encoder](https://www.kaggle.com/datasets/phmvittin/weight-asr)
2. [Visual_Encoder](https://www.kaggle.com/datasets/phmvittin/weight-cremad)

<!-- **Training Guidline** -->
<!-- This source code train with Kaggle using Pytorch version 
1. You need pip install timm version 0.4.5 for load Audio_Encoder
2. Using config.yaml to fix the name folder dataset, weight load
3. Run train_kaggle.inypb for training -->

## Getting Started
- Installation
``` bash
git clone https://github.com/PVTHust/Speech_project_Vin.git
```
- Download dataset: 
```bash
!gdown 1CdjCD2amHDsjJFfb5OuTbIfwEikgn6u-
```
- Unzip dataset:    
```bash
!unzip cremad.zip
```
-Train and evaluate our model:
```bash
!python /content/Speech_project_Vin/main.py
```


