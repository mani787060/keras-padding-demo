# Keras Padding Demo

## Overview
This notebook demonstrates the concept of **padding in Convolutional Neural Networks (CNNs)** using Keras.  
Padding plays a crucial role in preserving or reducing spatial dimensions during convolution operations.

Understanding padding is essential for designing efficient and deep CNN architectures.

## Objective
- Understand why padding is required in CNNs
- Compare different padding strategies
- Observe changes in feature map dimensions
- Implement padding using Keras Conv2D layers

## Padding Types Covered
- **Valid Padding**
  - No padding applied
  - Output size shrinks after convolution
- **Same Padding**
  - Zero padding added
  - Output spatial size preserved
- **Explicit Padding**
  - Manual padding using ZeroPadding2D

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Implementation Details
- Created sample input tensors
- Applied Conv2D layers with different padding strategies
- Compared input and output shapes
- Visualized feature map dimension changes

## Key Observations
- Valid padding reduces spatial dimensions
- Same padding preserves input dimensions
- Excessive padding increases computation cost
- Proper padding enables deeper CNN architectures

## Conclusion
Padding is a foundational CNN concept that affects feature extraction, depth scalability, and computational efficiency.  
This notebook provides a clear and practical understanding of padding behavior using Keras.
