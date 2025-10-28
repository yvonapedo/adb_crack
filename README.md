# The code will be available soon
#  ADB-Crack: A Transformer-Based Framework with Adaptive Context Fusion and Dynamic Feature Refinement for High-Precision Pavement Concrete Crack Segmentation


Authors: *Yvon Apedo*, Huanjie Tao, Chao Xie, Shusen Zhao 

---


---

## Usage
### Datasets
Download the Cracktree200, CrackForest, CrackLS315, and Stone331 dataset and the file follows the following structure.

```
|-- datasets
    |-- crack315
        |-- train
        |   |-- train.txt
        |   |--img
        |   |   |--<crack1.jpg>
        |   |--gt
        |   |   |--<crack1.bmp>
        |-- valid
        |   |-- Valid_image
        |   |-- Lable_image
        |   |-- Valid_result
        ......
```

train.txt format
```
./dataset/crack315/img/crack1.jpg ./dataset/crack315/gt/crack1.bmp
./dataset/crack315/img/crack2.jpg ./dataset/crack315/gt/crack2.bmp
.....
```
### Train

```
python train.py
```
### Valid

Change the 'pretrain_dir','datasetName' and 'netName' in test.py

```
python test.py
```

---
## Baseline Model Implementation

Our code references the code in [CRACKFORMER](https://github.com/LouisNUST/CrackFormer-II).

---

