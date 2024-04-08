# YOLO Object Detection from Scratch

This project implements a You Only Look Once (YOLO) object detection system from scratch using TensorFlow. The model is trained on the VOC 2012 Kaggle dataset and tested on the COCO 2017 dataset. The network architecture is based on EfficientNetB1 with additional convolutional and dense layers added to extend the network depth. The project includes features for handling XML annotations, visualizing results, training with data augmentation to reduce overfitting, and utilizing callbacks for training management.

## Architecture
![Architecture du modèle](https://github.com/HaykelBargouguy/Projects/assets/98351985/2cb1aaa3-b618-42be-8c5a-f2e7190023f7)

## Features

- XML File Annotation: The project supports handling XML annotation files for training data.
- Data Preprocessing: Images and their annotations are processed to be ready for use in the object detection network.
- Model Training: The YOLO model is trained on the VOC 2012 dataset using EfficientNetB1 as the base with additional layers.
- Evaluation on COCO Dataset: The trained model is evaluated on the COCO 2017 dataset to assess its performance.
- Custom Loss Function: Implements the YOLO loss function as described in the paper [You Only Look Once: Unified, Real-Time Object Detection](https://pjreddie.com/media/files/papers/yolo_1.pdf).
- Utilization of Callbacks: Callbacks are used to adjust learning rate and save the best models during training.
- Data Augmentation: To reduce overfitting, data augmentation techniques are employed during training.
- Results Visualization: Functions are provided to draw bounding boxes and visualize object detection results.

## Results 

![000000001000_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/540bec0b-3e3a-4f7b-aa55-ea0de417d427)
![000000005992_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/98c90a78-5252-4161-bab3-bd16366e9a9d)
![000000008690_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/ac5511da-1967-42ec-a758-4b6e3724db08)
![000000009448_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/17d911a5-f70c-43c0-b5db-66f70b1cbcc5)
![000000009483_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/4815ff01-c613-4d6f-adfc-2f77bdac30e7)
![000000017714_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/64b65d90-5317-4687-b71b-dea5f6b54564)
![000000020107 - Copy_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/befd7817-5ac7-4390-b24f-21bed6504aea)
![000000020107_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/51e1015f-1bb5-4a0b-8c73-9dd61d83e4ba)
![000000082821_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/d3d1e3b8-bf89-49a9-8c01-d50f76b8f9ca)
![000000083531_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/6c6fdf81-1297-4e5d-9a1c-6ab1d196f276)
![000000083540_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/7e0a3598-c831-45e9-9338-345088020fa4)
![000000084170 - Copy_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/898c7b32-45e8-4b9a-bac2-fcfbd7c0f1bf)
![000000084362 - Copy_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/38c4e7dd-c694-4c09-b832-a67af45d61f4)
![000000084362_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/92530576-3f27-4743-bf57-35f3a5e5f7fc)
![000000090155 - Copy_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/a6ed490d-dc26-425c-a79d-6f69fc2edba6)
![000000098261 - Copy_det](https://github.com/HaykelBargouguy/Projects/assets/98351985/a06a4877-a734-40e3-a4c1-455787e63c0a)

