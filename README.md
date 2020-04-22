# Content based Fine-Grained Image Retrieval using Convolutional Neural Network
A framework for content based fine-grained image retrieval (CB-FGIR) by using CNN is presented in [1]. 



more info can be found in [1].
**Results for Oxford Flower 17 dataset**
|Method|MAP|
|------|---|
|LBP|0.102|
|HOG|0.110 |
|Yang et al. [8] (Vgg-16) |87.72|
|ResNet18(Pretrained)|0.519 |
|Resnet-18(Pretrained + fine-tuned)|**0.928**|


**Results for cars-196 dataset**
|**Method**|SPOC [5]^3|CroW [7]^3| R-MAC [9]3| Wei et al. [12]| Resnet-18 (Pretrained+FineTuned)|
|--|--|--|--|--|--|
|**Dimension**|256|256|512|512|512|
|**Top1 MAP**|0.2986|0.4492|0.4654|0.5330|**0.84**|
|**Top2 MAP**|0.3623|0.5118|0.5298|0.5911|**0.80**


kindly cite this paper

[1] V. Kumar, V. Tripathi and B. Pant, "Content based Fine-Grained Image Retrieval using Convolutional Neural Network," 2020 7th International Conference on Signal Processing and Integrated Networks (SPIN), Noida, India, 2020, pp. 1120-1125.
