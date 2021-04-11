# CatsvsDogs
 SoC project 
 
Model 1 uses two layers of Conv2D and MaxPool2D i.e 4 layers in total.

Model 2 uses 2 layers of Conv2D.

Model 3 uses only 1 layer each of Conv2D and MaxPool2D
 
|Model no.| Arch |Epochs|  Acc  | Loss | Val_acc | Val_loss |Image1|Image2|Image3|
|:-------:|:----:|:----:|:-----:|:----:|:-------:|:--------:|:----:|:----:|:----:|
|   1     | 15,3 | 10   |1.0000 |0.0126 |0.6800 |1.1515  | 1|1|1|
|   1     | 8,3  | 10   |0.9879 |0.1098 |0.6600 |0.9471  |1|0|1|
|   1     | 2,3  | 10   |1.0000 |0.0114 |0.6230 |1.5235  |1|0|0|
|   2     | 15,3 | 10   |0.9981 |0.0050 |0.6340 |1.2895  |1|0|0| 
|   2     | 16,4 | 10   |1.0000 |0.0030 |0.6480 |1.3501  |1|0|0|
|   2     | 2,3  | 10   |0.9892 |0.0008 |0.5840 |1.9487  |1|0|1|
|   3     | 15,3 | 10   |0.9995 |0.0111 |0.6360 |1.7998  |1|0|0|
|   3     | 16,4 | 10   |1.0000 |0.0013 |0.6370 |1.9941  |1|0|0|

Best Model:=
Model 1, Arch (15,3)

|Image1|Image2|Image3|
| ---- | ---- | ---- |
| ![2021-04-11 (18)](https://user-images.githubusercontent.com/80119090/114308958-2b624600-9b03-11eb-92c6-1463b2bda341.png) | ![2021-04-11 (19)](https://user-images.githubusercontent.com/80119090/114308961-3321ea80-9b03-11eb-83b8-89fca2a92b44.png)  | ![2021-04-11 (20)](https://user-images.githubusercontent.com/80119090/114309046-79774980-9b03-11eb-9e49-ece4d7ba1ab9.png) |
