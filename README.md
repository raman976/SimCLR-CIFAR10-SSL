# SimCLR on CIFAR-10

This repo contains my implementation of the SimCLR self-supervised learning method on the CIFAR-10 dataset.

## What’s in the Notebook

- Training the SimCLR model from scratch with standard augmentations.  
- Evaluating learned features by training a simple linear classifier on CIFAR-10.  
- Reporting loss and accuracy results after training.

## How to Run

Open the notebook on Kaggle and run each cell in order. It will download the CIFAR-10 dataset and run the training and evaluation.

## Notes

- Training uses PyTorch and prefers GPU for speed but will run on CPU too.  
- The results show how well the model learns visual features without labels.

## References

- SimCLR paper by Ting Chen et al., 2020  
- CIFAR-10 dataset info: https://www.cs.toronto.edu/~kriz/cifar.html  
- PyTorch documentation: https://pytorch.org/docs/stable/
