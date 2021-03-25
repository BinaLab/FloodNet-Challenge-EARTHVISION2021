# FloodNet-Challenge-EARTHVISION2021

## Challenge Overview

Recent surge of natural disasters has caused human and economic losses across the world. 
The aftermath of these catastrophic disasters calls for quick humanitarian aid. However, manual rescue efforts are laborious and sometimes insufficient in reducing the great impact of natural disasters. Recently evolving techniques in computer vision can be used to tackle these challenges and assist first responders. Moreoever, analysis of high resolution post-disaster images is required that can help rescue efforts and reduce human as well as economic cost. 

[FloodNet](https://arxiv.org/abs/2012.02951) dataset provides high resolution UAV imageries with different types of damages such as as damaged buildings, roads, and neighborhoods. Inspired by this dataset and with an objective to perform a quick post disaster damage assessment, we propose a computer vision challenge on two tracks. 

 1. Track 1: Image Classification and Semantic Segmentation
 2. Track 2: Visual Question Answering


### Track 1

In this track, participants are required to complete two semi-supervised tasks. The first task is image classification, and the second task is semantic segmentation.

1. Semi-Supervised Classification: Classifying each image into 'Flooded' and 'Non-Flooded' categories with only a few training images having such labels available.
 
2. Semi-Supervised Semantic Segmentation: Pixel-wise classification of each image into multiple classes such as 'Road-Flooded', 'Road-Non-Flooded', 'Building-Flooded', 'Building-Non-Flooded' etc. Only a few training images have the pixel-wise masks available.

The dataset for Track 1 can be downloaded from this link: https://drive.google.com/drive/folders/1sZZMJkbqJNbHgebKvHzcXYZHJd6ss4tH?usp=sharing

### Track 2

Visual Question Answering: Visual question Answering is a multimodal task where a system provides an answer for a given question from an image. By asking the questions in natural language and getting the answers from those questions, we can understand the damage scenario comprehensively. "Is there any flooded road?", "How many flooded buildings are in the image?" - these types of questions will provide very crucial information and help the rescuers efficiently. In this track, we present the Visual Question Answering task for post-disaster damage assessment.
  
The dataset for Track 2 can be downloaded from this link: https://drive.google.com/drive/folders/1g1r419bWBe4GEF-7si5DqWCjxiC8ErnY?usp=sharing

### Paper Link
The paper can be downloaded from this [link](https://arxiv.org/abs/2012.02951).
Please cite our paper when using the dataset

 ```
@article{rahnemoonfar2020floodnet,
  title={FloodNet: A High Resolution Aerial Imagery Dataset for Post Flood Scene Understanding},
  author={Rahnemoonfar, Maryam and Chowdhury, Tashnim and Sarkar, Argho and Varshney, Debvrat and Yari, Masoud and Murphy, Robin},
  journal={arXiv preprint arXiv:2012.02951},
  year={2020}
}
```

