# FloodNet Dataset

## Overview

Frequent, and increasingly severe, natural disasters threaten human health, infrastructure, and natural systems. The provision of accurate, timely, and understandable information has the potential to revolutionize disaster management. For quick response and recovery on a large scale, after a natural disaster such as a hurricane, access to aerial images is critically important for the response team. The emergence of small unmanned aerial systems (UAS) along with inexpensive sensors presents the opportunity to collect thousands of images after each natural disaster with high flexibility and easy maneuverability for rapid response and recovery.  Moreover, UAS can access hard-to-reach areas and perform data collection  tasks that can be unsafe for humans if not impossible.  Despite all these advancements and efforts to collect such large datasets, analyzing them and extracting meaningful information remains a significant challenge in scientific communities.

[FloodNet](https://arxiv.org/abs/2012.02951) provides high-resolution UAS imageries with detailed semantic annotation regarding the damages. To advance the damage assessment process for post-disaster scenarios, we present a unique challenge considering classification, semantic segmentation, visual question answering highlighting the UAS imagery-based FloodNet dataset.

 1. Track 1: Image Classification and Semantic Segmentation
 2. Track 2: Visual Question Answering

## Dataset Details

The data is collected with a small UAS platform, DJI Mavic Pro quadcopters, after Hurricane Harvey. The whole dataset has 2343 images, divided into training (~60%), validation (~20%), and test (~20%) sets.

For Track 1 ( Semi-supervised Classification and Semantic Segmentation),  in the training set, we have around 400 labeled images (~25% of the training set) and around 1050 unlabeled images (~75% of the training set ).

For Track 2 ( Supervised VQA), in the training set we have around 1450 images and there are a total 4511 image-question pairs.   


### Track 1

In this track, participants are required to complete two semi-supervised tasks. The first task is image classification, and the second task is semantic segmentation.

1. Semi-Supervised Classification: Classification for FloodNet dataset requires classifying the images into ‘Flooded’ and ‘Non-Flooded’ classes. Only a few of the training images have their labels available, while most of the training images are unlabeled. 
 
2. Semi-Supervised Semantic Segmentation: The semantic segmentation labels include: 1) Background, 2) Building Flooded, 3) Building Non-Flooded, 4) Road Flooded, 5) Road Non-Flooded, 6) Water, 7)Tree, 8) Vehicle, 9) Pool, 10) Grass. 
Only a small portion of the training images have their corresponding masks available. 

The dataset for Track 1 can be downloaded from this link: https://drive.google.com/drive/folders/1sZZMJkbqJNbHgebKvHzcXYZHJd6ss4tH?usp=sharing

### Track 2

For the Visual Question Answering (VQA) task, we provide images associated with multiple questions. These questions will be divided into the following categories:

1. Simple Counting: Questions will be designed to count the number of objects regardless of their attribute. For example: “how many buildings are there in the image?”.
2. Complex Counting: Questions will be asked to count the number of objects belonging to a specific attribute. For example: “how many flooded buildings are there in the image?”.
3. Condition Recognition: In this category, all the questions are mainly designed to ask questions regarding the condition of the object and the neighborhood. For example: “What is the condition of the road in the given image?”.
4. Yes/No type of question: For this type of question, the answer will be either a ‘Yes’ or a ‘No’. For example: “Is there any flooded road?”.

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

