# RiceLeafImage
# RiceLeaf Disease Detection

## Overview
The RiceLeaf Disease Detection project aims to develop a model capable of accurately categorizing three primary diseases affecting rice plants: leaf smut, bacterial blight, and brown spot. The project involves data analysis, model development, and exploration of various techniques, including data augmentation, to enhance the model's accuracy.

## Dataset
The dataset comprises 119 images depicting rice leaves affected by bacterial leaf blight, brown spot, and leaf smut. Each image is labeled with one of the three disease classes.

### Disease Classes
#### Bacterial Leaf Blight:
- **Overview:** Caused by Xanthomonas oryzae pv. oryzae, bacterial leaf blight induces water-soaked lesions on rice leaves, leading to tissue death.
- **Symptoms:** Elongated water-soaked lesions surrounded by a yellow halo, which progress to leaf wilting and necrosis.
- **Prevention and Management:** Strategies include using disease-resistant rice varieties and minimizing overhead irrigation.

#### Brown Spot:
- **Overview:** Caused by Bipolaris oryzae, brown spot leads to circular to elliptical spots with dark centers and yellow halos on rice leaves.
- **Symptoms:** Small water-soaked lesions evolving into brown patches, hindering photosynthesis.
- **Prevention and Management:** Measures include using disease-resistant varieties and practicing proper field hygiene.

#### Leaf Smut:
- **Overview:** Caused by Entyloma oryzae, leaf smut forms smut masses containing fungal spores on rice leaves.
- **Symptoms:** Small smut masses with powdery spores, impairing photosynthesis.
- **Prevention and Management:** Practices involve planting disease-free seeds and maintaining good field sanitation.

## Project Details
### Data Analysis
We conducted comprehensive data analysis on the dataset, preparing it for subsequent stages of the project. The dataset consists of 119 images distributed among three disease classes.

### Data Preprocessing
We performed the following preprocessing steps:
- **Image Size:** Resized images to 256x256 pixels.
- **Batch Size:** Set to 8.
- **Number of Epochs:** 50.
- **Data Loading:** Utilized TensorFlow's image dataset loading functionality.
- **Data Augmentation:** Applied techniques such as rotation, shifts, and flips.
- **Train-Validation-Test Split:** Allocated 80% for training, 10% for validation, and 10% for testing.
- **Data Caching and Prefetching:** Optimized training efficiency using TensorFlow's capabilities.

### Image Display
We visually inspected the training dataset to verify the success of preprocessing steps and gain insights into the classes.

## Usage
To use this project:
1. Clone the repository.
2. Install dependencies specified in `requirements.txt`.
3. Run the provided scripts for data analysis, preprocessing, and model training.

## Contribution Guidelines
Contributions to the project are welcome! If you'd like to contribute, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and ensure they pass tests.
- Submit a pull request detailing your changes.

## License
This project is licensed under the [MIT License](LICENSE).
