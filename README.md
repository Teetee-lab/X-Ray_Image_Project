# X-Ray_Image_Project
![X-ray machine](https://www.thegreatcoursesdaily.com/wp-content/uploads/2021/03/Xray-Feature.jpg)

## Project Overview
This notebook contains our steps to solving a data science predictive modeling image classification problem. Which involves the Chest X-rays Images from pediatric patients of one of five years old from childrens's Medical Center. Our aim is to develop an accurate model that predicts whether or not a patient have pneumonia based on the X-ray images. After trying different models we decided to use a pretrained CNN model VGG19 and decided to tune it with our dataset and then test it on unseen dataset to see how it performed. We convert the learning problem into an optimization problem, define a loss function and then optimize the algorithm to minimize the loss function.

## Data Overview
We obtained our data from Kaggle: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia which was originally sourced from Mendeley:https://data.mendeley.com/datasets/rscbjbr9sj/3
- The data is organized into three different folders (train,val,test) and each contains subfolders for each category. 
- There are 5863 X-Ray images(JPEG) and 2 categories with are (PNEUMONIA/NORMAL).

## Methodology
The methodology we used for building the model are:
- Neural Network 
- Convolutional Neural Network
- VGG19 Pretrained CNN 

## Project Result
The VGG19 Pretrained Model predict an accuracy score of 90% on unseen data(test set). We recommend the Doctors and Radiology Society to employ our predictive model to identify which patients have Pneumonia and the risk. Our model will also help the Radiology Society reduce grading errors.

## Next Steps
- Gather more Dataset
- Improve Precision
- Apply model to covid 19 X-ray images

## Repository Navigation
- Data
- Notebook
- ChestXRayImageProject notebook
- Presentation pdf
- Readme

## AUthors
- Titilayo Amuwo(Teetee)
- Paul Shin
- Tony Bennett
