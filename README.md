# Estimation and Analysis of Slice Propagation Uncertainty in 3D Anatomy Segmentation
Code release is pending and will be made available upon paper acceptance.

## Paper
- [Archive Version](https://arxiv.org/abs/2403.12290)

## Visual Demonstrations
Our study integrates Uncertainty Quantification (UQ) methods into slice propagation techniques for medical image analysis, aiming to enhance prediction accuracy and reliability with minimal expert supervision. The GIFs provided below serve as a visual representation of this integration, highlighting the critical role of UQ in improving the confidence and accuracy of predictions.

*Inference Starting Point and Propagation from the Annotated Slice:*
The starting point of inference begins at the the anatomy's largest manually annotated slice. From this annotated slice, the propagation process extends in both directions, one slice at a time. It's important to note that the GIF animations display the slice propagation process from the very first slice to the last slice of the volume. Within this sequence, there is a critical point to observe: the annotated slice, which can be identified by where the model's predicted annotation aligns most closely with the ground truth, and uncertainty is at its minimum. 

----------------------------
**UQ-Enhanced Slice Propagation Example 1:**
![](GIFs/DecathSpleen_Vol28.gif)

**UQ-Enhanced Slice Propagation Example 2:**
![](GIFs/SLiver07_Vol02.gif)

----------------------------

These visual demonstartions allow us to observe how the model's confidence and accuracy evolve as it moves away from the initial high-confidence point. As the propagation advances, a gradient of uncertainty becomes evident — uncertainty increases and accuracy decreases the further we move from the annotated slice. This dynamic illustrates the inherent challenges of slice propagation and underscores the value of UQ in estimating and understanding these variations.

## Datasets Used

- [**DecathSpleen**](http://medicaldecathlon.com/)

- [**CHAOS**](https://chaos.grand-challenge.org/)

- [**SLiver**](https://sliver07.grand-challenge.org/)


