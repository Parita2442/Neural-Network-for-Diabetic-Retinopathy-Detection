# BA865 - Neural Networks
## Group Project BA865

# Detection of Diabetic Retinopathy through Fundus Images

![Fundus Image 1](https://github.com/mwangcy/BA865/assets/143052952/1246901e-50ba-4666-80ee-809c6b2a8319)

![Fundus Image 2](https://github.com/mwangcy/BA865/assets/143052952/e54536d2-dc2a-4b1a-aec7-0b8596d5b40d)

## Collaborators
- **Aishwarya Jayant Rauthan**
- **Mauro Wang**
- **Parita Patel**

## Motivation
According to the International Diabetes Federation, the occurrence of diabetes in the adult population (20-79 years) is projected to increase by 46% by the year 2045. Diabetic retinopathy (DR) is a consequential complication of diabetes, characterized by damage to the retina at the back of the eye. If left untreated, DR can lead to loss of vision, hence early detection is imperative. Our project aims to use deep neural networks to identify and detect symptoms of DR to facilitate timely treatment.

## Dataset
The dataset comprises fundus images from the IDRiD dataset, captured by a retinal specialist at an Eye Clinic in Nanded, Maharashtra, India. It includes a reasonable mixture of disease stratification representative of diabetic retinopathy (DR) and diabetic macular edema (DME). The dataset also provides information regarding the disease severity level of DR and DME. Grading for all images is available in a CSV file categorized according to the International Clinical Diabetic Retinopathy Scale:

- **0** - No abnormalities
- **1** - Mild nonproliferative diabetic retinopathy
- **2** - Moderate nonproliferative diabetic retinopathy
- **3** - Severe nonproliferative diabetic retinopathy
- **4** - Proliferative diabetic retinopathy

The dataset includes 516 images with a resolution of 4288×2848 pixels stored in jpg file format, with each image being about 800 KB.

- **Data Source:** [IDRiD](https://idrid.grand-challenge.org/Data/)
- **Data Download Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/abdullahshafi315/indian-diabetic-retinopathy-image-datasetidrid)

## Models Used
- Logistic Regression
- KMeans Clustering
- Convolutional Neural Networks (CNN)
- Vision Transformer (ViT)
- EfficientNet
- ResNet
