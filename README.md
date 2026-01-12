# Credit Card Fraud Detection using GANs
This project explores the use of Generative Adversarial Networks (GANs) to handle class imbalance in credit card fraud detection.

## Dataset
The Credit Card Fraud Detection dataset from Kaggle is used.
Due to size and license restrictions, the dataset is not included.

## Implemented GAN Models
- Vanilla GAN
- Conditional GAN (CGAN)
- Wasserstein GAN (WGAN)

All GANs are trained using only the minority (fraud) class.

## Project Structure
- `notebook/` contains the implementation code
- `report/` contains the final project report

## How to Run
1. Download the dataset from Kaggle
2. Place `creditcard.csv` in the working directory
3. Open the notebook and run all cells

## Evaluation
Models are evaluated using Accuracy, Precision, Recall, and F1-score.
