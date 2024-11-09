
# Satellite Imagery Land Cover Classification Using U-Net with ResNet50

This project demonstrates a method for land cover classification from satellite imagery using a U-Net model enhanced with a ResNet50 encoder. The combination of these architectures results in highly accurate segmentation of land cover, offering a reliable solution for geospatial analysis. The model's practical implementation includes a web-based interface, allowing for easy interaction and real-time results.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [References](#references)
- [License](#license)

## Overview

This repository provides a solution for land cover classification using satellite imagery. The model is built using a U-Net architecture with ResNet50 as the encoder. The encoder-decoder architecture with residual connections allows the model to efficiently capture both high-level and fine-grained features, resulting in high-performance segmentation masks. The web-based interface allows users to easily interact with the model for classification tasks.

## Features

- **High Accuracy**: The U-Net with ResNet50 architecture offers exceptional performance in land cover classification.
- **Web Interface**: A user-friendly web interface for easy interaction with the model.
- **Segmentation Masks**: The model outputs detailed segmentation masks that classify different land cover types.
- **Flexible**: The architecture can be extended to other geospatial tasks beyond land cover classification.

## Requirements

- Python 3.7+
- TensorFlow
- Keras
- OpenCV
- Flask (for web interface)
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/land-cover-classification.git
   ```

2. Navigate to the project directory:
   ```bash
   cd land-cover-classification
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. (Optional) Set up a virtual environment if you prefer to keep dependencies isolated.

## Usage

1. Train the model using the training dataset by running:
   ```bash
   python train.py
   ```

2. Launch the web interface:
   ```bash
   python app.py
   ```

   This will start a local server on port 5000, and you can access the model via your browser at `http://localhost:5000`.

3. Upload a satellite image, and the model will process it to generate segmentation masks.

## Results

The U-Net with ResNet50 architecture performs exceptionally well on satellite imagery, achieving high classification accuracy in land cover tasks. The model outputs segmentation masks that can be easily interpreted and integrated into other geospatial analysis workflows.

## References

1. Safarov, F., Temurbek, K., Jamoljon, D., Temur, O., Chedjou, J. C., Abdusalomov, A. B., & Cho, Y. I. (2022). Improved agricultural field segmentation in satellite imagery using TL-ResUNet architecture. Sensors, 22(24), 9784. [Link](https://doi.org/10.3390/s22249784)

2. Zhang, Z., Lu, W., Cao, J., & Xie, G. (2022). MKANet: An efficient network with Sobel boundary loss for land-cover classification of satellite remote sensing imagery. Remote Sensing, 14(18), 4514. [Link](https://doi.org/10.3390/rs14184514)

3. Siddique, A., Li, Z., Azeem, A., Zhang, Y., & Xu, B. (2023). Multiscale Context-Aware Feature Fusion Network for Land Cover Classification of Urban Scene Imagery. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing. DOI: 10.1109/JSTARS.2023.3310160

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
