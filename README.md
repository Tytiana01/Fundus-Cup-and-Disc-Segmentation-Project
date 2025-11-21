This project trains and compares U-Net and a Fully Convolutional Network (FCN) for optic cup and optic disc segmentation using SLO fundus images from the FairSeg dataset. Both models output three-class masks: background, optic disc, optic cup, and performance is evaluated using the Dice similarity coefficient.

The study also measures Dice scores across racial groups (Asian, Black, White) to analyze whether segmentation performance is consistent and fair.

Key Details

Input: 256×256 grayscale fundus images

Models: U-Net (skip connections) vs FCN (no skips)

Optimizer: Adam (lr=1e-4)

Epochs: 10 with early stopping

Metric: Dice score (overall + per-race)

This work aims to support fair and equitable glaucoma detection by evaluating whether deep learning models perform similarly across demographic groups.
