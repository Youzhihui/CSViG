# Siamese Vision Graph Neural Network with Cross Feature Fusion for Remote Sensing Image Change Detection

This project contains the implementation of our work for semi-supervised semantic segmentation:
`Siamese Vision Graph Neural Network with Cross Feature Fusion for Remote Sensing Image Change Detection`

## News
Repo is created in 2022-11-5. Code will come soon.

## Abstract
With the development of deep learning in remote sensing (RS) visual tasks, RS image change detection (CD) has achieved remarkable progress. However, RS bi-temporal images cover complex and confusing scenes due to natural environmental factors, which poses challenges to CD task. How to effectively exploit long-range dependencies and sensitively discriminate real-changes from pseudo-changes are urgent problems. This paper presents a CD approach using Siamese Vision Graph neural network (SViG) with cross feature fusion. SViG acts as a feature extractor to capture richer long-range dependencies. Cross feature fusion consists of a horizontal feature fusion module (HFFM) and a vertical feature fusion module (VFFM). HFFM designs cross-concatenation way to reveal real-changes in the same horizontal stage, after which global and local features are extracted by using attention mechanism and multi-scale depth-wise separable convolution. VFFM further fuses complementary content from vertical multiple stages to represent change region by using attention mechanism. Extensive comparative experiments on three public CD datasets demonstrate that the proposed method achieves the best CD performance. 
