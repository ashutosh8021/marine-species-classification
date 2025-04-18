# Marine Species Classifier using Deep Learning

This project uses transfer learning with **ResNet18** to classify images of marine species. It also includes **Grad-CAM visualization** to interpret model predictions.

## Demo
Run the notebook directly on [Google Colab](https://colab.research.google.com/drive/1FBxn6e1rQ8msVECg1YBdJuizbPexzQmi?usp=sharing/).

## Tech Stack
- Python
- PyTorch
- Google Colab
- OpenCV
- Matplotlib
- Torchvision (ResNet18)
- Grad-CAM (for explainability)

## Dataset
Marine Species Dataset from [Kaggle](https://www.kaggle.com/datasets/sripaadsrinivasan/fish-species-image-dataset).

## Features
- Image classification using transfer learning
- Model trained and evaluated on 9+ marine species
- Grad-CAM for model interpretability

## How to Run
1. Clone this repository  
   `git clone https://github.com/ashutosh8021/marine-species-classification.git`

2. Open the notebook  
   `Marine Species Classifier using Deep learning.ipynb` in [Google Colab](https://colab.research.google.com/drive/1FBxn6e1rQ8msVECg1YBdJuizbPexzQmi?usp=sharing/)

3. Upload dataset and model checkpoint

4. Run all cells to test predictions and visualize with Grad-CAM

## Results
- Achieved 84% validation accuracy 
- Effective class activation heatmaps for visual feedback

## Credits
- Dataset: Kaggle community
- Base model: ResNet18 from torchvision
- Developed by: [Ashutosh Kumar](https://www.linkedin.com/in/ashutosh80/)
