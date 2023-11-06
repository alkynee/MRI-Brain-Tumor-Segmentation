
# MRI-Brain-Tumor-Segmentation
This repository contains comprehensive code to perform segmentation and morphological operations, fundamental to image processing. Building upon these concepts, a solution to detect and extract tumors from MRI brain scans, using Python, is also demonstrated.

**METHODOLOGY**:

The solution involves a two-step process involving the pre-processing of the given MRI image, followed by segmentation and morphological operations. The steps of the algorithm are as follows:

1) Take a MRI image of the brain as input.
2) Convert it to a grayscale image.
3) Perform threshold-based segmentation.
4) Apply watershed segmentation.
5) Carry out morphological operations.
6) The final output will be the region identified as a tumor.

**OUTPUT**:

![Thresholding](Sample-Outputs/Thresholding.PNG)

![segmentation](Sample-Outputs/Segmentation.PNG)