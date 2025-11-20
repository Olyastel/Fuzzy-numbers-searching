# Fuzzy Scooter Number Recognition

A research project focused on developing and evaluating fuzzy search algorithms for identifying electric scooters from damaged or partially visible identification numbers. This module specifically handles image-based character similarity analysis to improve OCR and search accuracy.

## Project Description

In large-scale fleet management, identifying scooters from blurred or damaged numbers is a common challenge. This project explores SSIM metric to create a robust search system that can handle real-world data imperfections where traditional exact matching fails.

## Features

- **Image Similarity Analysis**: Uses Structural Similarity Index (SSIM) to compare character images
- **Character Recognition Support**: Generates similarity matrices for OCR post-processing
- **Configurable Thresholding**: Flexible similarity thresholds for different accuracy requirements
- **Batch Processing**: Efficient processing of multiple character images

## Installation

```bash
# Clone repository
git clone https://github.com/Olyastel/Fuzzy-numbers-searching

# Install dependencies
pip install numpy pandas pillow scikit-image
```

## QR-код для быстрого доступа

<div align="center">

### Отсканируйте чтобы открыть на телефоне

![QR Code](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://github.com/Olyastel/Fuzzy-numbers-searching)

[📎 https://github.com/Olyastel/Fuzzy-numbers-searching](https://github.com/Olyastel/Fuzzy-numbers-searching)

</div>