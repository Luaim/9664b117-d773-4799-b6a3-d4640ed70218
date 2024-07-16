# Pet Image Classifier Project

## Overview
This project implements a pet image classifier using pre-trained CNN models to classify images of pets, particularly focusing on identifying dog breeds. It includes functionality to classify images, calculate statistics, and print results based on comparisons between pet labels and classifier predictions.

## Project Structure
- `check_images.py`: Main script for image classification.
- `get_pet_labels.py`: Module to retrieve and format pet image labels.
- `classify_images.py`: Module to classify pet images using pre-trained CNN models.
- `calculate_results_stats.py`: Module to calculate and print statistics on classification results.
- `print_results.py`: Module to format and print summary results including misclassifications.

## Requirements
- Python 3.x
- TensorFlow or PyTorch (depending on the CNN model used)
- Additional Python libraries (specified in requirements.txt)

## Installation
1. Clone the repository:

git clone https://github.com/Luaim/Pet-Image-Classifier
cd pet-image-classifier

2. Install dependencies:

pip install -r requirements.txt


## Usage
### Running the Classifier
1. Navigate to the project directory:

cd pet-image-classifier

2. Run the classifier using default settings:

python check_images.py

- Optional Arguments:
  - `--dir`: Specify the directory containing pet images (default: 'pet_images/')
  - `--arch`: Choose the CNN architecture ('vgg', 'resnet', 'alexnet') (default: 'vgg')
  - `--dogfile`: Specify the file containing dog names for classification (default: 'dognames.txt')

### Classifying Uploaded Images
1. Prepare images in the `uploaded_images/` folder.
2. Run classification for uploaded images:

sh run_models_batch_uploaded.sh


### Printing Results
1. Print summary results including misclassifications:


python print_results.py


## Results
- Detailed results for each CNN model architecture: VGG, ResNet, AlexNet.
- Compare accuracy and performance based on provided statistics and misclassifications.

## Contributors
- [Luai] https://github.com/Luaim
- Udacity: Provided the course materials and guidance.
- AWS Educate: Provided resources and support for the scholarship.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

