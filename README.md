# Vehicle Detection from Low Resolution Images

A deep learning project combining R-ESRGAN for image enhancement and YOLOv4 for vehicle detection.

## Overview
- Enhances low-resolution images using pretrained R-ESRGAN
- Detects vehicles using pretrained YOLOv4
- Input: Low-resolution vehicle images
- Output: Enhanced images with vehicle detection boxes



## Requirements
```
pytorch>=1.7.0
opencv-python>=4.5.0
numpy>=1.19.0
real-esrgan>=0.3.0
darknet>=0.3.0
```

## Model Attribution

### Real-ESRGAN
- Source: https://github.com/xinntao/Real-ESRGAN
- License: BSD 3-Clause
```
@article{wang2021realesrgan,
  title={Real-ESRGAN: Training Real-World Blind Super-Resolution with Pure Synthetic Data},
  author={Wang, Xintao and Xie, Liangbin and Dong, Chao and Shan, Ying},
  journal={arXiv:2107.10833},
  year={2021}
}
```

### YOLOv4
- Source: https://github.com/AlexeyAB/darknet
- License: MIT License
```
@article{bochkovskiy2020yolov4,
  title={YOLOv4: Optimal Speed and Accuracy of Object Detection},
  author={Bochkovskiy, Alexey and Wang, Chien-Yao and Liao, Hong-Yuan Mark},
  journal={arXiv:2004.10934},
  year={2020}
}
```

## Acknowledgments
This project uses pretrained R-ESRGAN and YOLOv4 models. All rights belong to their respective authors.

For research and educational purposes only.

## Contact

- Author: Viresh Patel
- Email: patelvir30@gmail.com
- GitHub: [@thevireshpatel]https://github.com/thevireshpatel
