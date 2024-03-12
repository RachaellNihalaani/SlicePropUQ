# Estimation and Analysis of Slice Propagation Uncertainty in 3D Anatomy Segmentation
## Paper
- [Archive Version]()

## Visual Demonstrations
Our study integrates Uncertainty Quantification (UQ) methods into slice propagation techniques for medical image analysis, aiming to enhance prediction accuracy and reliability with minimal expert supervision. The GIFs provided below serve as a visual representation of this integration, highlighting the critical role of UQ in improving the confidence and accuracy of predictions.

*Inference Starting Point and Propagation from the Annotated Slice:*
The starting point of inference begins at the the anatomy's largest manually annotated slice. From this annotated slice, the propagation process extends in both directions, one slice at a time. It's important to note that the GIF animations display the slice propagation process from the very first slice to the last slice of the volume. Within this sequence, there is a critical point to observe: the annotated slice, which can be identified by where the model's predicted annotation aligns most closely with the ground truth, and uncertainty is at its minimum. 

These visual demonstartions allow us to observe how the model's confidence and accuracy evolve as it moves away from the initial high-confidence point. As the propagation advances, a gradient of uncertainty becomes evident — uncertainty increases and accuracy decreases the further we move from the annotated slice. This dynamic illustrates the inherent challenges of slice propagation and underscores the value of UQ in estimating and understanding these variations.

_Purpose of GIFs:_ These GIFs are intended to visually demonstrate the progression of slice propagation enhanced by UQ methods. By observing the propagation process from a slice where the model's confidence is highest, viewers can appreciate the nuanced improvements UQ brings to the reliability and accuracy of segmentation predictions.

UQ-Enhanced Slice Propagation Example 1:
![](GIFs/DecathSpleen_Vol28.gif)

UQ-Enhanced Slice Propagation Example 2:
![](GIFs/SLiver07_Vol02.gif)

These visual demonstrations are a vivid illustration of how UQ integration can dynamically improve the trustworthiness and effectiveness of slice propagation techniques. By observing the full sequence, including the critical annotated slice and the variations beyond it, viewers can gain a comprehensive understanding of the nuanced impact of UQ on enhancing model reliability and prediction accuracy in medical image analysis.
