# vision-foundations
A collection of large scale & foundation vision transformers useful for downstream task

# Task-based

## Image Encoder (best for classification)
  | Title & Authors | Architecture & Pretrained | Finetune Dataset | Useful Links |
  |:----|  :----: | :---:| :---:|
  | [![Star](https://img.shields.io/github/stars/mlfoundations/open_clip.svg?style=social&label=Star)](https://github.com/mlfoundations/open_clip) <br>[**(2022) OPENCLIP**](https://github.com/mlfoundations/open_clip) <br> *Mehdi Cherti, Romain Beaumont, Ross Wightman, Mitchell Wortsman, Gabriel Ilharco, Cade Gordon, Christoph Schuhmann, Ludwig Schmidt, Jenia Jitsev* | ViT-B/32 <br> ViT-B/16 <br> ViT-L/14 <br> ViT-H/14 <br> ViT-g/14 <br> ViT-G/14| [LAION-400M](https://laion.ai/laion-400-open-dataset/) <br> [LAION-2B](https://laion.ai/blog/laion-5b/) | [Github](https://github.com/mlfoundations/open_clip) |
  | [![Star](https://img.shields.io/github/stars/deepglint/unicom.svg?style=social&label=Star)](https://github.com/deepglint/unicom) <br>[**(ICLR-2023) UNICOM**](https://github.com/deepglint/unicom) <br> *Xiang An, Jiankang Deng, Kaicheng Yang, Jaiwei Li, Ziyong Feng, Jia Guo, Jing Yang, Tongliang Liu* | ViT-B/32 <br> ViT-B/16 <br> ViT-L/14 | [LAION-400M](https://laion.ai/laion-400-open-dataset/) | [Github](https://github.com/deepglint/unicom) |
  | [![Star](https://img.shields.io/github/stars/facebookresearch/dinov2.svg?style=social&label=Star)](https://github.com/facebookresearch/dinov2) <br>[**(2023) DINOv2: Learning Robust Visual Features without Supervision**](https://github.com/facebookresearch/dinov2) <br> *Maxime Oquab, Timothée Darcet, Théo Moutakanni, Huy Vo, Marc Szafraniec, Vasil Khalidov, Pierre Fernandez, Daniel Haziza, Francisco Massa, Alaaeldin El-Nouby, Mahmoud Assran, Nicolas Ballas, Wojciech Galuba, Russell Howes, Po-Yao Huang, Shang-Wen Li, Ishan Misra, Michael Rabbat, Vasu Sharma, Gabriel Synnaeve, Hu Xu, Hervé Jegou, Julien Mairal, Patrick Labatut, Armand Joulin, Piotr Bojanowski* | ViT-S/14 <br> ViT-B/14 <br> ViT-L/14 <br> ViT-g/14 | LVD142M (private dataset from META) | [Github](https://github.com/facebookresearch/dinov2) |
  | [![Star](https://img.shields.io/github/stars/LouieShao/1st-Place-Solution-in-Google-Universal-Image-Embedding.svg?style=social&label=Star)](https://github.com/LouieShao/1st-Place-Solution-in-Google-Universal-Image-Embedding) <br>[**(2022) Google Universal Object Embedding (Top 1)**](https://github.com/LouieShao/1st-Place-Solution-in-Google-Universal-Image-Embedding) <br> *Shihao Shao, Qinghua Cui* | [ViT-H/14 (LAION-2B)](https://github.com/mlfoundations/open_clip) | [Products-10K](https://products-10k.github.io/) <br/> [Shopee](https://www.kaggle.com/competitions/shopee-product-matching/data) <br/> [MET Artwork Dataset](https://www.kaggle.com/competitions/shopee-product-matching/data) <br/> [Alibaba goods](https://www.kaggle.com/datasets/dschettler8845/the-met-dataset)<br/> [H&M Personalized Fashion](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data)<br/> [GPR1200](https://www.kaggle.com/code/vitaliykinakh/gpr1200-benchmark-images-retrieval/data)<br/> [GLDv2-Full](https://github.com/cvdfoundation/google-landmark)<br/> [DeepFashion - Consumer-to-shop Clothes Retrieval Benchmark part](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)<br/> | [Github](https://github.com/LouieShao/1st-Place-Solution-in-Google-Universal-Image-Embedding) |
  | [![Star](https://img.shields.io/github/stars/XL-H/ECCV2022.svg?style=social&label=Star)](https://github.com/XL-H/ECCV2022) <br>[**(2022) Google Universal Object Embedding (Top 2)**](https://github.com/XL-H/ECCV2022) <br> *Xiaolong Huang, Qiankun Li* | [ViT-H/14 (LAION-2B)](https://github.com/mlfoundations/open_clip) | [Aliproducts](https://tianchi.aliyun.com/competition/entrance/231780/introduction) <br> [Art_MET](https://www.kaggle.com/datasets/dschettler8845/the-met-dataset) <br> [DeepFashion(Consumer-to-shop)](https://www.kaggle.com/datasets/sangamman/deepfashion-consumer-to-shop-training) <br> [DeepFashion2(hard-triplets)](https://www.kaggle.com/datasets/sangamman/deepfashion2-hard-triplets) <br> [Fashion200K](https://www.kaggle.com/datasets/mayukh18/fashion200k-dataset) <br> [ICCV 2021 LargeFineFoodAI](https://www.kaggle.com/competitions/largefinefoodai-iccv-recognition/data) <br> [Food Recognition 2022](https://www.kaggle.com/datasets/sainikhileshreddy/food-recognition-2022) <br> [JD_Products_10K](https://www.kaggle.com/c/products-10k) <br> [Landmark2021](https://www.kaggle.com/competitions/landmark-retrieval-2021) <br> [Grocery Store](https://github.com/marcusklasson/GroceryStoreDataset) <br> [rp2k](https://www.pinlandata.com/rp2k_dataset/) <br> [Shopee](https://www.kaggle.com/competitions/shopee-product-matching) <br> [Stanford_Cars](https://ai.stanford.edu/~jkrause/cars/car_dataset.html) <br> [Stanford_Products](https://cvgl.stanford.edu/projects/lifted_struct/) <br> | [Github](https://github.com/XL-H/ECCV2022) |
  

## Segment
  | Title & Authors | Intro | Useful Links |
  |:----|  :----: | :---:|
  | [![Star](https://img.shields.io/github/stars/facebookresearch/segment-anything.svg?style=social&label=Star)](https://github.com/facebookresearch/segment-anything) <br> [**(2023) Segment Anything**](https://arxiv.org/abs/2304.02643) <br> *Alexander Kirillov, Eric Mintun, Nikhila Ravi, Hanzi Mao, Chloe Rolland, Laura Gustafson, Tete Xiao, Spencer Whitehead, Alex Berg, Wan-Yen Lo, Piotr Dollar, Ross Girshick* | ![intro](https://github.com/facebookresearch/segment-anything/blob/main/assets/masks2.jpg?raw=true) | [[Github](https://github.com/facebookresearch/segment-anything)] <br> [[Page](https://segment-anything.com/)] <br> [[Demo](https://segment-anything.com/demo)] <br> [[Dataset](https://ai.facebook.com/datasets/segment-anything-downloads/)] |
  | [![Star](https://img.shields.io/github/stars/SysCV/sam-hq.svg?style=social&label=Star)](https://github.com/SysCV/sam-hq) <br>[**(2023) Segment Anything in High Quality**](https://github.com/SysCV/sam-hq) <br> *Lei Ke, Mingqiao Ye, Martin Danelljan, Yifan Liu, Yu-Wing Tai, Chi-Keung Tang, Fisher Yu* | ![intro](https://github.com/SysCV/sam-hq/blob/main/visual_demo/1.gif) | [Github](https://github.com/SysCV/sam-hq) |
  | [![Star](https://img.shields.io/github/stars/CASIA-IVA-Lab/FastSAM.svg?style=social&label=Star)](https://github.com/CASIA-IVA-Lab/FastSAM) <br>[**(2023) Fast Segment Anything**](https://github.com/CASIA-IVA-Lab/FastSAM) <br> *Xu Zhao, Wenchao Ding, Yongqi An, Yinglong Du, Tao Yu, Min Li, Ming Tang, Jinqiao Wang* | ![intro](https://github.com/CASIA-IVA-Lab/FastSAM/blob/main/assets/head_fig.png) | [Github](https://github.com/CASIA-IVA-Lab/FastSAM) |
  | [![Star](https://img.shields.io/github/stars/ChaoningZhang/MobileSAM.svg?style=social&label=Star)](https://github.com/ChaoningZhang/MobileSAM) <br>[**(2023) Faster Segment Anything (MobileSAM)**](https://github.com/ChaoningZhang/MobileSAM) <br> *Zhang, Chaoning and Han, Dongshen and Qiao, Yu and Kim, Jung Uk and Bae, Sung-Ho and Lee, Seungkyu and Hong, Choong Seon* | ![intro](https://github.com/ChaoningZhang/MobileSAM/raw/master/assets/mask_point.jpg) | [Github](https://github.com/ChaoningZhang/MobileSAM) |

## Text Recognition
  | Title & Authors | Architecture & Pretrained | Finetune Dataset | Intro | Useful Links |
  |:----|  :----: | :---:| :---:| :---:|
  | [![Star](https://img.shields.io/github/stars/Mountchicken/Union14M.svg?style=social&label=Star)](https://github.com/Mountchicken/Union14M) <br>[**(ICCV-2023) Revisiting Scene Text Recognition: A Data Perspective**](https://github.com/Mountchicken/Union14M) <br> *Qing Jiang , Jiapeng Wang , Dezhi Peng , Chongyu Liu , Lianwen Jin* | ViT-S/4, ViT-B/4 ([Union14M - 4M labeled images, 10M unlabeled images](https://github.com/Mountchicken/Union14M#34-download))| [Union14M - 4M labeled images, 10M unlabeled images](https://github.com/Mountchicken/Union14M#34-download) | ![intro](https://user-images.githubusercontent.com/65173622/242812266-bcfdd369-decd-4b6f-903b-3021531bd119.png) | [Github](https://github.com/Mountchicken/Union14M) |
  
# Object-based

## Person Embedding
  | Title & Authors | Architecture & Pretrained | Finetune Dataset | Intro | Useful Links |
  |:----|  :----: | :---:| :---:| :---:|
  | [![Star](https://img.shields.io/github/stars/Zplusdragon/PLIP.svg?style=social&label=Star)](https://github.com/Zplusdragon/PLIP) <br>[**(2023) PLIP: Language-Image Pre-training for Person Representation Learning**](https://github.com/Zplusdragon/PLIP) <br> *Shuyu Yang, Yinan Zhou, Yaxiong Wang, Yujiao Wu, Li Zhu, Zhedong Zheng* | Resnet50, BERT ([SYNTH-PEDES - 4.8M images, 312k IDs, 12M captions](https://github.com/Zplusdragon/PLIP#synth-pedes)) | [CUHK-PEDES](http://xiaotong.me/static/projects/person-search-language/dataset.html) <br> [ICFG-PEDES](https://github.com/zifyloo/SSAN) <br> [Market1501](https://zheng-lab.cecs.anu.edu.au/Project/project_reid.html) <br> [DukeMTMC](http://vision.cs.duke.edu/DukeMTMC/) <br> [PETA](http://mmlab.ie.cuhk.edu.hk/projects/PETA.html) <br> [PA-100K](https://github.com/xh-liu/HydraPlus-Net) <br> [RAP](https://www.rapdataset.com/rapv2.html) | ![intro](https://github.com/Zplusdragon/PLIP/blob/main/assets/abstract.png) | [Github](https://github.com/Zplusdragon/PLIP) |
  | [![Star](https://img.shields.io/github/stars/Shuyu-XJTU/APTM.svg?style=social&label=Star)](https://github.com/Shuyu-XJTU/APTM) <br>[**(2023) Towards Unified Text-based Person Retrieval: A Large-scale Multi-Attribute and Language Search Benchmark**](https://github.com/Shuyu-XJTU/APTM) <br> *Shuyu Yang, Yinan Zhou, Yaxiong Wang, Yujiao Wu, Li Zhu, Zhedong Zheng* | SwinTransformer-B ([MALS - 1.5M images, 27 attributes](https://github.com/Shuyu-XJTU/APTM#mals)) | [CUHK-PEDES](http://xiaotong.me/static/projects/person-search-language/dataset.html) | ![intro](https://github.com/Shuyu-XJTU/APTM/blob/main/assets/framework.jpg) | [Github](https://github.com/Shuyu-XJTU/APTM) |

