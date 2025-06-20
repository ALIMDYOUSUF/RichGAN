![Generated images by using 10 and 5 captions on CUB-200 and MS-COCO test set](https://github.com/user-attachments/assets/70e41c9f-d2ca-4cb3-9d9a-472ac0b1da54)# RichGAN: A Rich-Attention Embedding Framework for Fine-Grained Semantic Alignment in Generative Adversarial Training

![RichGAN-based Figure](https://github.com/user-attachments/assets/ddb20595-19ba-4e71-9b58-0fa1b6cb68e5)

![RAEM Figure](https://github.com/user-attachments/assets/5524b81b-c955-42c8-b6e6-fc8f8bfd7dab)



---

## Requirements
- python 3.12
- Pytorch 2.2.0
- NVIDIA RTX 4070-Ti GPUs 
## Installation

Clone this repo.
```
git clone [https://github.com/tobran/DMF-GAN](https://github.com/ALIMDYOUSUF/RichGAN)
pip install -r requirements.txt
cd RichGAN/code/
```

## Preparation
### Datasets
1. Download the preprocessed metadata for [birds](https://drive.google.com/file/d/1I6ybkR7L64K8hZOraEZDuHh0cCJw5OUj/view?usp=sharing) [coco](https://drive.google.com/file/d/15Fw-gErCEArOFykW3YTnLKpRcPgI_3AB/view?usp=sharing) and extract them to `data/`
2. Download the [birds](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) image data. Extract them to `data/birds/`
3. Download [coco2014](http://cocodataset.org/#download) dataset and extract the images to `data/coco/images/`


## Training
  ```
  cd RichGAN/code/
  ```
### Train the DF-GAN model
For bird dataset: python main.py --cfg cfg/bird.yml

For coco dataset: python main.py --cfg cfg/coco.yml



**Reference**
-  [[code]](https://github.com/xueqinxiang/DMF-GAN) (DMF-GAN)
-  [[code]](https://github.com/senmaoy/RAT-GAN) (RAT-GAN)
-  [[code]](https://github.com/hanzhanggit/StackGAN-v2) (StackGAN-v2)
-  [[code]](https://github.com/taoxugit/AttnGAN) (AttnGAN)



