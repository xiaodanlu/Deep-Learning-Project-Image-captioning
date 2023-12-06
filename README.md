# DSAN6600-Project
DSAN6600, Group 06 --- Yunhong Yang, Ziyue Li, Yutao Chen, Xiaodan Lu

## Table of contents
* Abstract
* Repository structure

## Abstract
Image captioning, a task that involves describing the content of an image through words, represents a unique intersection between computer vision and natural language processing (NLP). This study focuses on image captioning with an emphasis on the COCO dataset. The richness and diversity of the COCO dataset play a crucial role in training and evaluating image captioning models, and addressing challenges in recognizing, interpreting, and describing visual elements within images. Data preprocessing, including text cleaning, resizing, and tokenization, ensures a high-quality dataset. The model was built based on the pre-existing InceptionV3 model, adding additional layers to enhance its ability to predict captions. Evaluation metrics such as BLEU, METEOR, and ROUGE scores highlight promising aspects of the model's learning, indicating potential areas for refinement. The project suggests future research directions, emphasizing the importance of diverse datasets and architectural adjustments for improved performance in image captioning, contributing valuable insights to this dynamic field.

## Repository structure

You will work within an **organized** repository and apply coding and development best practices. The repository has the following structure:

```.
├── LICENSE
├── README.md
├── code/
├── data/
```
* The `code/` directory is where we develop all our code. 

* The `data/` directory contains our data files. The Coco Dataset used in this project can be downloaded through the following [link](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset). "selected_data_10000.json" contains the final 10,000 images with captions that we chose to work on for our project.

## Model

There are two .ipynb files in  `code/` directory about our project and with different models: **Model.ipynb** and **Vit-GPT2 Model.ipynb**. 

With **Model.ipynb**: We use COCO dataset.

With **Vit-GPT2 Model.ipynb**: We use Flickr8K dataset, and use pre-trained model: vit-GPT2 from [Huggingface](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning/tree/main). While the model inherently possesses advanced capabilities in processing images and generating text, **fine-tuning** allows it to refine these skills based on the particular characteristics and requirements of the Flickr8K dataset.

Our written-up is focus on the **Model.ipynb**.







