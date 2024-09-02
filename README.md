# Convolutional Neural Networks Step by Step
This notebook covers the implementation of convolutional (CONV) and pooling (POOL) layers using numpy.

## Contents
1. Introduction
2. Packages
3. Assignment Outline
4. Convolutional Neural Networks
    - Zero-Padding
    - Single Step of Convolution
    - Forward Pass
5. Pooling Layer
    - Forward Pooling
6. Backpropagation (Optional)
    - Convolutional Layer Backward Pass
    - Pooling Layer Backward Pass

## Introduction
Implement the building blocks of a CNN from scratch using numpy.

## Packages
- `numpy`
- `matplotlib`

## Assignment Outline
Functions to implement:
- Convolution functions: Zero Padding, Convolve Window, Convolution Forward, Convolution Backward (optional)
- Pooling functions: Pooling Forward, Create Mask, Distribute Value, Pooling Backward (optional)

## Convolutional Neural Networks
### Zero-Padding
Adds zeros around the border of an image.

### Single Step of Convolution
Apply a filter to a single position of the input.

### Forward Pass
Convolve multiple filters on the input to produce a 3D volume of outputs.

## Pooling Layer
### Forward Pooling
Reduces the height and width of the input.

## Backpropagation (Optional)
### Convolutional Layer Backward Pass
Compute gradients for the input, weights, and biases.

### Pooling Layer Backward Pass
Max and average pooling backward pass.

---

Feel free to customize further!
