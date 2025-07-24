# SPANet: Road Defect Detection via Scale- and Patch-Aware Attention

[![Pytorch](https://img.shields.io/badge/PyTorch-1.9+-EE4C2C.svg)](https://pytorch.org/)
[![MMSegmentation](https://img.shields.io/badge/MMSegmentation-1.x-007EC6.svg)](https://github.com/open-mmlab/mmsegmentation)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)

Official implementation of SPANet: A dual-attention network for robust road defect detection (cracks & potholes) built upon MMSegmentation.

## Key Features
- 🎯 **Attention Mechanism**: 
  - Scale-aware attention for multi-granularity feature fusion
  - Patch-aware attention to suppress noise in skip connections
- 🚀 **SOTA Performance**: 1.93% higher Dice score than prior methods
- 🏗 **MMSeg Compatible**: Seamless integration with OpenMMLab ecosystem
- 🌍 **Multi-Scenario Robustness**: Tested on multiple scenarios

## Installation
```bash
# Step 1: Install MMSegmentation
pip install -U openmim
mim install mmengine mmcv
mim install mmsegmentation

# Step 2: Clone SPANet
git clone https://github.com/yourusername/SPANet.git
cd SPANet
```
