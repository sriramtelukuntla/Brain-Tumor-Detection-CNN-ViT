# Brain-Tumor-Detection

A comparative study of CNN and Vision Transformer (ViT) models 
for automatic brain tumor classification from MRI images.

## Project Structure
- `project brain tumor(CNN)/CNN.ipynb` — CNN model training and evaluation
- `project brain tumor(VITs)/vision transformers.ipynb` — ViT model training and evaluation

## Models Used
- Convolutional Neural Network (CNN) — built with TensorFlow/Keras
- Vision Transformer (ViT) — built with HuggingFace Transformers + PyTorch

## Tumor Classes
- Glioma
- Meningioma
- Pituitary
- No Tumor

## Dataset
Dataset not included due to size. Download from Kaggle:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

## How to Run
1. Open the notebooks in Google Colab
2. Mount your Google Drive
3. Place the dataset in your Drive as shown in the notebook paths
4. Run all cells in order

## Requirements
See `requirements_CNN.txt` and `requirements_ViT.txt`

## Results
| Model | Accuracy |
|-------|----------|
| CNN   |    98%   |
| ViT   |    100%  |

## Tools & Technologies
Python, TensorFlow, Keras, PyTorch, Transformers,
Google Colab, Gradio, Scikit-learn, OpenCV
