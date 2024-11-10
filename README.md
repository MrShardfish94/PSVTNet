This is the official codes and data for the work "Pathological image segmentation of breast cancer via template matching". All codes and dataset will be accessible as well as this work is accepted formally.

Accurate pathological image segmentation is crucial for the clinical diagnosis of breast cancer. However, existing methods of pathological segmentation face challenges due to the variability and complexity of breast cancer on pathological images. To address these issues, we propose a novel segmentaion network called  template-matching pathological segmentation network (PSVTNet). PSVTNet incorporates an innovative template matching strategy inspired by the diagnostic process of pathologists. The core of this strategy is to utilize visual transformer (ViT) to establish a correlative relationship between cancer lesions and corresponding templates. These templates are collected from clinical cases that contain various and representative features of breast cancer in terms of morphology and texture. When considering to facilitate integration and utilization of features for pathological images, PSVTNet arranges detailed information attention (DIA) and information entropy attention (IEA) into detail-and-information guidance decoder. DIA aims to exploit detailed information, but also serves as the path connecting shallow-layer and deep-layer features. Meanwhile, IEA is employed to redistribute model weights to high-entropy regions for further refining segmentation results. Additionally, this work releases a comprehensive pathological dataset called C-Path4k, which consists of three types of cancers for evaluating the generalization of PSVTNet. C-Path4k comprises 4437 labeled pathological images of HE-stained breast cancer, HER2-stained breast cancer, and HE-stained stomach cancer. Extensive experiments demonstrate that PSVTNet significantly outperforms state-of-the-art methods, especially in handling zero-shot datasets.

Visualized results on coinsistent data:
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a4de8df76ffd4d5690d80585ae552ea1.png)

Visualized results on incoinsistent data:
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8291dd26e61e4c5ba23309ebfc558a5b.png)

Codes and C-Path4k can be download for the [Baidu Netdisk link](https://pan.baidu.com/s/1f5iN1Jyb9K2rpe1hJUAlWg%29)


