
# Leukemia Detection Using Deep Learning and Vision Transformer (ViT)

This repository presents a deep learning solution for the automated detection of leukemia in blood smear images, leveraging the Vision Transformer (ViT) architecture. The goal of this project is to assist in the early detection of leukemia, providing a reliable and efficient tool that can potentially support medical diagnostics.



## Project Overviw
Leukemia, a cancer of the blood and bone marrow, requires early detection for effective treatment. Traditional methods of diagnosing leukemia involve time-consuming manual examination of blood smear images by experts. In this project, we propose a deep learning-based approach that automates this process using the cutting-edge Vision Transformer (ViT) model. ViT is a novel architecture that treats images as sequences of patches, enabling it to capture complex patterns and relationships in the image data, making it an ideal choice for medical image analysis.
## Key Features

Vision Transformer Architecture: Adopts the transformer model, which processes images by splitting them into patches and learning representations via self-attention mechanisms.
Data Augmentation: Utilizes various augmentation techniques such as rotation, flipping, and scaling to enhance model robustness and prevent overfitting.
Transfer Learning: Fine-tunes a pre-trained ViT model on the leukemia dataset to improve classification performance.
Comprehensive Evaluation: The model is evaluated using metrics like accuracy, precision, recall, F1-score, and the Area Under the Curve (AUC) for a thorough performance assessment.
## Model Architecture

This project utilizes the Vision Transformer (ViT), a transformer-based architecture designed for image classification. The key advantage of ViT is its ability to model long-range dependencies within an image by treating image patches as tokens, akin to words in natural language processing models. For this project, we fine-tune a pre-trained ViT model to classify blood smear images into two categories: Leukemia and Non-Leukemia.
## Dataset

The dataset used for this project consists of blood smear images that are labeled for the presence of leukemia. Preprocessing steps such as resizing the images to 224x224 pixels and normalizing the pixel values are applied. Additionally, various augmentation techniques (random rotations, flips, etc.) are employed to improve the model’s ability to generalize to unseen data.

Classes: Leukemia and Non-Leukemia
Preprocessing: Images are resized, normalized, and augmented to ensure model robustness.
## Conclusion

This project demonstrates the applicability of Vision Transformer models for the early detection of leukemia in blood smear images. By automating the diagnostic process, this model provides an efficient and scalable solution that can aid healthcare professionals in making faster, more accurate diagnoses. Future work may involve further model tuning, deployment of the model in clinical settings, and integration with broader diagnostic workflows.
## Acknowledgements


This project was inspired by the groundbreaking work on Vision Transformers and leverages publicly available medical datasets for leukemia detection. Special thanks to the developers of the Vision Transformer architecture and the contributors to the open-source libraries that made this project possible.