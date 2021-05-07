# Lung-Cancer-Segmentation

https://www.kaggle.com/kmader/finding-lungs-in-ct-data

Those codes are based on U-Net network

![unet](https://user-images.githubusercontent.com/36688650/117411171-42535700-af4e-11eb-9fd4-7c6e8af0387d.gif)

## U-Net + VGG

VGG backbone network + U-Net

loss is [Binary Cross Entropy Jaccard Loss]
metric is [iou_score]

![다운로드 (3)](https://user-images.githubusercontent.com/36688650/117411752-e76e2f80-af4e-11eb-8d25-3caa82e28d9b.png)

### requirement
https://github.com/qubvel/segmentation_models

keras
opencv


## U-Net 512 by 512

Can change size (256, 512)

loss is [Binary Cross Entropy]
metric is [dice coefficient]


![unnamed](https://user-images.githubusercontent.com/36688650/117412113-59df0f80-af4f-11eb-8e09-43736b75749b.png)
