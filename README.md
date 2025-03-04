# ADOPD: A Large-Scale Document Page Decomposition Dataset

![image](preview.png)

Research in document image understanding is limited by the lack of high-quality data. To address this, we introduce **ADOPD**, a large-scale dataset for document page decomposition. Unlike existing datasets, ADOPD uses a novel data-driven taxonomy discovery method, combining large-scale pretrained models with human-in-the-loop validation to ensure diversity and balance. ADOPD includes densely annotated document images for four tasks: **Doc2Mask, Doc2Box, Doc2Tag, and Doc2Seq**. Each image comes with human-labeled entity masks, text bounding boxes, and automatically generated tags and captions. We provide experiments to validate our taxonomy method and analyze model performance across these tasks. We believe ADOPD will serve as a key resource for advancing document image understanding research.

## ADOPD Dataset

### Authors
Jiuxiang Gu, Xiangxi Shi, Jason Kuen, Lu Qi, Ruiyi Zhang, Anqi Liu, Ani Nenkova, Tong Sun

## Download Annotation Files
The dataset annotations can be downloaded [here](https://github.com/adobe-research/adopd2024/releases/tag/v1.0).

## Download Images
Images can be downloaded through the image source entries and/or URLs provided in the `json` file. Please note that we do not own the copyright of the images. It is solely your responsibility to check the original licenses of the images before using them. Any use of the images is at your own discretion and risk.

## Citation
Please cite our ICLR 2024 paper if you use the ADOPD dataset in your work:
```bibtex
@inproceedings{
    gu2024adopd,
    title={{AD}o{PD}: A Large-Scale Document Page Decomposition Dataset},
    author={Jiuxiang Gu and Xiangxi Shi and Jason Kuen and Lu Qi and Ruiyi Zhang and Anqi Liu and Ani Nenkova and Tong Sun},
    booktitle={The Twelfth International Conference on Learning Representations},
    year={2024},
    url={https://openreview.net/forum?id=x1ptaXpOYa}
}
