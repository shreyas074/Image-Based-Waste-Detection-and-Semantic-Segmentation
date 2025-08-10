# Image-Based-Waste-Detection-and-Semantic-Segmentation
This project implements an image-based waste detection and semantic segmentation pipeline that identifies and segments litter in natural scenes. The system trains a pixel-level segmentation model on the TACO dataset and outputs segmentation masks and visualizations suitable for environmental monitoring and automated waste analysis.

The primary goal of this project is to classify and accurately localize different waste categories within an image, enabling applications such as:

- Automated waste sorting systems in recycling plants

- rban cleanliness monitoring for municipalities

- Environmental research to study waste distribution patterns

The implemented model is based on an encoder-decoder architecture that performs pixel-level classification, generating segmentation masks that highlight waste objects within the scene. By analyzing both global image context and fine object details, the system achieves robust detection even in cluttered or complex environments.

# Requirements
The project requires the following Python packages:
- Python 3.8+

- NumPy

- OpenCV

- PyTorch

- torchvision

- matplotlib

- scikit-learn

- tqdm


### You can install dependencies with:
pip install numpy opencv-python torch torchvision matplotlib scikit-learn tqdm

# Dataset
The TACO dataset is an open image dataset for litter detection.
It can be downloaded from the official repository: http://tacodataset.org/
