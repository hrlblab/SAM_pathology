# Segment Anything Model (SAM) for Digital Pathology: Assess Zero-shot Segmentation on Whole Slide Imaging

This is the official implementation of Segment Anything Model (SAM) for Digital Pathology: Assess Zero-shot Segmentation on Whole Slide Imaging. <br />

**MIDL2023 Paper** <br />
> [Segment Anything Model (SAM) for Digital Pathology: Assess Zero-shot Segmentation on Whole Slide Imaging](https://arxiv.org/pdf/2304.04155.pdf) <br />
> Ruining Deng, Can Cui, Quan Liu, Tianyuan Yao, Lucas W. Remedios, Shunxing Bao, Bennett A. Landman, Lee E. Wheless, Lori A. Coburn, Keith T. Wilson, Yaohong Wang, Shilin Zhao, Agnes B. Fogo, Haichun Yang, Yucheng Tang, Yuankai Huo  <br />
> *MIDL2023 conference* <br />

## Abstract
The segment anything model (SAM) was released as a foundation model for image segmentation. The promptable segmentation model was trained by over 1 billion masks on 11M licensed and privacy-respecting images. The model supports zero-shot image segmentation with various segmentation prompts (e.g., points, boxes, masks). It makes the SAM attractive for medical image analysis, especially for digital pathology where the training data are rare. In this study, we evaluate the zero-shot segmentation performance of SAM model on representative segmentation tasks on whole slide imaging (WSI), including (1) tumor segmentation, (2) non-tumor tissue segmentation, (3) cell nuclei segmentation.  <br /> 

The results suggest that the zero-shot SAM model achieves remarkable segmentation performance for large connected objects. However, it does not consistently achieve satisfying performance for dense instance object segmentation, even with 20 prompts (clicks/boxes) on each image. We also summarized the identified limitations for digital pathology: (1) image resolution, (2) multiple scales, (3) prompt selection, and (4) model fine-tuning. 

## Quick Start
#### Get our docker image
Todo

#### Run code
Todo


## Citation
```
@article{deng2023segment,
  title={Segment anything model (sam) for digital pathology: Assess zero-shot segmentation on whole slide imaging},
  author={Deng, Ruining and Cui, Can and Liu, Quan and Yao, Tianyuan and Remedios, Lucas W and Bao, Shunxing and Landman, Bennett A and Wheless, Lee E and Coburn, Lori A and Wilson, Keith T and others},
  journal={arXiv preprint arXiv:2304.04155},
  year={2023}
}
```
