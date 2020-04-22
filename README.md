# Content based Fine-Grained Image Retrieval using Convolutional Neural Network
A framework for content based fine-grained image retrieval (CB-FGIR) by using CNN is presented in [6]. More info can be found in the [**paper**](https://ieeexplore.ieee.org/document/9071334).

**Results for Oxford Flower 17 dataset**
|Method|MAP|
|------|---|
|LBP|0.102|
|HOG|0.110 |
|Yang et al. [1] (Vgg-16) |0.8772|
|ResNet18(Pretrained)|0.519 |
|Resnet-18(Pretrained + fine-tuned)|**0.928**|


**Results for cars-196 dataset**
|**Method**|SPOC [2]*|CroW [3]*| R-MAC [4]*| Wei et al. [5]| Resnet-18 (Pretrained+FineTuned)|
|--|--|--|--|--|--|
|**Dimension**|256|256|512|512|512|
|**Top1 MAP**|0.2986|0.4492|0.4654|0.5330|**0.84**|
|**Top2 MAP**|0.3623|0.5118|0.5298|0.5911|**0.80**


[1] H. Yang, K. Lin, and C. Chen. "Cross-batch reference learning for deep classification and retrieval." In Proceedings of the 24th ACM international conference on Multimedia, 2016, pp. 1237-1246.\
[2] A. B. Yandex and V. Lempitsky, "Aggregating Local Deep Features for Image Retrieval," 2015 IEEE International Conference on Computer Vision (ICCV), Santiago, 2015, pp. 1269-1277\
[3] Y. Kalantidis, C. Mellina, and S. Osindero. "Cross-dimensional weighting for aggregated deep convolutional features." In European
conference on computer vision, Springer, Cham, 2016, pp. 685-701.\
[4] G. Tolias, R. Sicre, and H. Jégou. "Particular object retrieval with integral max-pooling of CNN activations." arXiv preprint arXiv:1511.05879, 2015\
[5] X. Wei, J. Luo, J. Wu and Z. Zhou, "Selective Convolutional Descriptor Aggregation for Fine-Grained Image Retrieval," in IEEE Transactions on Image Processing, vol. 26, no. 6, pp. 2868-2881, June 2017.


If you find it useful, kindly cite this paper:

**[6] V. Kumar, V. Tripathi and B. Pant, "Content based Fine-Grained Image Retrieval using Convolutional Neural Network," 2020 7th International Conference on Signal Processing and Integrated Networks (SPIN), Noida, India, 2020, pp. 1120-1125.**
