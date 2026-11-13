# lung-segmentation-unet
# Lung Segmentation with U-Net (Chest X-rays)

A U-Net convolutional neural network for lung segmentation on chest X-ray images, built with TensorFlow.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](PASTE_COLAB_LINK_HERE)

## Results
- Dice score: 0.95
- IoU score: 0.91
- Evaluated on a held-out test set of 704 images

## Dataset
Chest X-rays from the Montgomery County and Shenzhen datasets released by the U.S. National Library of Medicine:
- Images: https://archive.nlm.nih.gov/repos/chestImages.php (request access via the NLM contact there)
- Shenzhen lung masks: https://www.kaggle.com/datasets/yoctoman/shcxr-lung-mask/data

The images are not included in this repo. Download them from the links above and update the paths in the notebook.

Citation: Jaeger S, Candemir S, Antani S, Wáng YXJ, Lu PX, Thoma G. Two public chest X-ray datasets for computer-aided screening of pulmonary diseases. Quant Imaging Med Surg. 2014;4(6):475-7.

## How to run
1. Click the Colab badge above.
2. Run all cells in order.

## Notes
Research project completed with Global Science Journey (Apr-Sep 2025).
