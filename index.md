# Mosquito Detection

## Introduction & Problem Statement

Mosquitoes are one of the leading killers of humans, killing over one million people a year. Identifying and detecting them can go a long way in eliminating mosquitoes. By leveraging a convolutional neural network, we hope to distinguish mosquitoes from other insects.

## Data

I gathered insect images from various sources, including kaggle, a research university in France, and the US department of agriculture. There was a lot of manual work that had to be done to crop the images and retain the best possible image quality.

## Model

I converted the images to matrices and then used data augmentation. This was done to prevent overfitting and help the model generalize to new data and because of a small initial dataset.

## Conclusion and Todo

The results were better than I expected with a validation accuracy score 0.84 on the best model. A lot more fine tuning can be done to improve the model. Next todo is to process and analyze video to detect mosquitoes.
