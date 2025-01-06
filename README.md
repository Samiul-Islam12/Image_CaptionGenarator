---
title: Image Captioning
emoji: 🦀
colorFrom: red
colorTo: gray
sdk: streamlit
sdk_version: 1.10.0
app_file: app.py
pinned: false
---
# Image Caption Generator Using Deep Learning

Effective image understanding is a cornerstone of modern AI applications. This project focuses on generating natural language captions for images, blending the power of computer vision and natural language processing. By leveraging the Flickr8k and COCO datasets, the model learns to associate visual features with descriptive text.


The model is deployed live on [Hugging Face Spaces (https://huggingface.co/spaces/sami-2429/ImageCaptionGenarator), providing an intuitive interface for users to upload images and receive automatically generated captions. This implementation makes the technology accessible to developers and researchers alike.


## Screenshot

![Web App Screenshot](https://github.com/Samiul-Islam12/Image_CaptionGenarator/blob/main/Screenshot%202025-01-06%20142448.jpg)

## To run click here:
To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    https://github.com/Samiul-Islam12/Image_CaptionGenarator
    cd Image_CaptionGenarator
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the `image_captioning_coco_weights.h5` and `image_captioning_transformer_weights_2.h5` file from the [GDrive]([https://drive.google.com/file/d/1OIo7oakSxPU3K51Cqnz6Dk1hsF16JuOu](https://drive.google.com/drive/folders/1J_yJHmF3ePh0yA6CpU5bNLR2lBYw5tt8?usp=sharing)) link and replace it with `image_captioning_coco_weights.h5` and `image_captioning_transformer_weights_2.h5`.


## Acknowledgement

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k). and (https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset)


## To run the model click here(live on higging face):
https://huggingface.co/spaces/sami-2429/ImageCaptionGenarator

