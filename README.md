# SPANet: Road Defect Detection via Scale- and Patch-Aware Attention

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

# 3. Install dependencies
pip install -r requirements.txt
```

## Quick Start

1. Dataset Preparation

Organize data in MMSeg format

2. Train
```
python tools/train.py [CONFIG FILE]
```
3. Test
```
python tools/test.py [CONFIG FILE] [MODEL DIR]
```

## License

This project is released under the Apache 2.0 License. For details see the `LICENSE` file.

## Acknowledgement
This library is constructed based on the following repos:
- MMsegmentation https://github.com/open-mmlab/mmsegmentation
