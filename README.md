# Awesome Object Shadow Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to object shadow generation, which aims to generate plausible shadow for the inserted foreground object in a composite image.

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Other Resources](#Other-resources)


## Papers

#### Supervised deep learning methods
+ Yan Hong, Li Niu, Jianfu Zhang: "*Shadow Generation for Composite Image in Real-world Scenes.*" AAAI (2022) [[arXiv]](https://arxiv.org/pdf/2104.10338v1.pdf) [[dataset]](https://github.com/bcmi/Object-Shadow-Generation-Dataset-DESOBA)
+ Yichen Sheng, Yifan Liu, Jianming Zhang, Wei Yin, Oztireli Cengiz, He Zhang, Lin Zhe, Shechtman Eli, Bedrich Benes: "*Controllable Shadow Generation Using Pixel Height Maps*" ECCV (2022) [[arXiv]](https://arxiv.org/pdf/2207.05385.pdf) [[Project]](https://shengcn.github.io/SSG/)
+ Yichen Sheng, Jianming Zhang, Bedrich Benes: "*SSN: Soft shadow network for image compositing*" CVPR (2021) oral [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sheng_SSN_Soft_Shadow_Network_for_Image_Compositing_CVPR_2021_paper.pdf)  [[code]](https://github.com/ShengCN/SSN_SoftShadowNet) [[Project]](https://shengcn.github.io/SSN/)
+ Daquan Liu, Chengjiang  Long, Hongpan Zhang, Hanning Yu, Xinzhi  Dong, Chunxia Xiao: "*ARshadowGAN: Shadow generative adversarial network for augmented reality in single light scenes.*" CVPR (2020) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_ARShadowGAN_Shadow_Generative_Adversarial_Network_for_Augmented_Reality_in_Single_CVPR_2020_paper.pdf) [[code]](https://github.com/ldq9526/ARShadowGAN)
+ Shuyang Zhang, Runze Liang, Miao Wang: "*ShadowGAN: Shadow synthesis for virtual objects with conditional adversarial networks.*" Computational Visual Media (2019) [[pdf]](https://link.springer.com/content/pdf/10.1007/s41095-019-0136-1.pdf)

#### Unsupervised deep learning methods

+ Fangneng Zhan, Shijian Lu, Changgong Zhang, Feiying Ma, Xuansong Xie: "*Adversarial Image Composition with Auxiliary Illumination.*" ACCV (2020) [[pdf]](https://openaccess.thecvf.com/content/ACCV2020/papers/Zhan_Adversarial_Image_Composition_with_Auxiliary_Illumination_ACCV_2020_paper.pdf)

#### Traditional methods

+ Bin Liao, Yao Zhu, Chao Liang, Fei Luo, Chunxia Xiao: "*Illumination animating and editing in a single picture using scene structure estimation.*" Computers & Graphics (2019) [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0097849319300627)

+ Bin Liu, Kun Xu, Ralph R. Martin: "*Static scene illumination estimation from videos with applications.*" Journal of Computer Science and Technology (2017) [[pdf]](https://link.springer.com/content/pdf/10.1007/s11390-017-1734-y.pdf)

+ Kevin Karsch, Kalyan Sunkavalli, Sunil Hadap, Nathan Carr, Hailin Jin, Rafael Fonte, Michael Sittig, David Forsyth: "*Automatic scene inference for 3d object compositing.*" ACM Transactions on Graphics (2014) [[arXiv]](https://arxiv.org/pdf/1912.12297.pdf)

+ Kevin Karsch, Varsha Hedau, David Forsyth, Derek Hoiem: "*Rendering synthetic objects into legacy photographs.*" ACM Transactions on Graphics (2011) [[arXiv]](https://arxiv.org/pdf/1912.11565.pdf)


## Datasets

+ **Shadow-AR**:  It contains 3,000 quintuples,  Each quintuple consists of 5 images 640×480 resolution: a synthetic image without the virtual object shadow and its corresponding image containing the virtual object shadow, a mask of the virtual object, a labeled real-world shadow matting and its corresponding labeled occluder. [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_ARShadowGAN_Shadow_Generative_Adversarial_Network_for_Augmented_Reality_in_Single_CVPR_2020_paper.pdf) [[link]](https://github.com/ldq9526/ARShadowGAN)
+ **DESOBA**: It contains 840 training images with totally 2,999 object-shadow pairs and 160 test images with totally 624 object-shadow pairs. [[pdf]](https://arxiv.org/pdf/2104.10338v1.pdf) [[link]](https://github.com/bcmi/Object-Shadow-Generation-Dataset-DESOBA)
 
## Other Resources

+ [Awesome-Image-Composition](https://github.com/bcmi/Awesome-Image-Composition)

