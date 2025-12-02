# Fuzzy scooter number recognition

A research project focused on developing and evaluating fuzzy search algorithms for identifying electric scooters from damaged or partially visible identification numbers. This module specifically handles image-based character similarity analysis to improve OCR and search accuracy.

## Project description

In large-scale fleet management, identifying scooters from blurred or damaged numbers is a common challenge. This project explores SSIM metric to create a robust search system that can handle real-world data imperfections where traditional exact matching fails.

## Features

- **Image similarity analysis**: uses Structural Similarity Index (SSIM) to compare character images
- **Character recognition support**: generates similarity matrices for OCR post-processing
- **Configurable thresholding**: flexible similarity thresholds for different accuracy requirements
- **Batch processing**: efficient processing of multiple character images
- **Visual similarity integration**: uses pre-computed character similarity matrix for intelligent substitutions
- **Priority-based search**: explores most likely character combinations first using heap optimization
- **Regex pattern matching**: converts fuzzy queries into efficient regular expressions
- **Configurable limits**: time and result count constraints for real-time applications
- **Benchmarking tools**: built-in performance measurement and test data generation

## Installation

```bash
# Clone repository
git clone https://github.com/Olyastel/Fuzzy-numbers-searching

# Install dependencies
pip install numpy pandas pillow scikit-image matplotlib
```

## QR code for quick access

<div align="center">

### Scan it to open it on your phone

![QR Code](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://github.com/Olyastel/Fuzzy-numbers-searching)

[https://github.com/Olyastel/Fuzzy-numbers-searching](https://github.com/Olyastel/Fuzzy-numbers-searching)

</div>
