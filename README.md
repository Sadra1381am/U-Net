# Enhancing Deep Learning Robustness in Microscopy Images Project

### By: Sadra Moazzen, Maricruz Díaz, Jiawei Kong, Cherishma Subhasa

### TAs: Vivek Sagar, Soan Kim

## Project Overview

This project focuses on improving the robustness of deep learning models, particularly U-Net, in microscopy image segmentation. The primary challenges include dealing with noise and artifacts in the images.

## Research Question

How can deep learning models be made more robust to noise and artifacts in microscopy images to improve prediction accuracy?

## Methods

- **Dataset**: Autosegmentation of Cultured Neurons Dataset
- **Model**: U-Net (CNN with encoder-decoder structure and skip connections)
- **Optimizer**: Adamax
- **Data Augmentation**: Rotations, resizing, cropping, translations, and horizontal flipping
- **Noise**: Speckle noise

## Results

The model's robustness was improved by adding noise, data augmentation, and hyperparameter tuning. Detailed results are provided in the [report](Magnificent_Lupin(GroupA).pdf).

## Files

- `new_unet.ipynb`: Jupyter notebook containing the code for the U-Net model and experiments.
- `Magnificent_Lupin(GroupA).pdf`: Project report detailing the methods, results, and conclusions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
