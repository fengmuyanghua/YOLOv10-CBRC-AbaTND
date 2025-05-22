YOLOv10-CBRC/AbaTND

Project Overview: This project is designed for document layout analysis tasks.

Dataset Description:
Provides a Tibetan newspaper dataset containing 571 images with corresponding TXT format annotations, suitable for both detection and segmentation tasks (users need to implement custom code for annotation format conversion).

Directory Structure:

images
├── /train
├── /val
└── /test

labels
├── /train
├── /val
└── /test

Model Description:
Based on the YOLOv10n baseline model, we improved the PSA, upsample, SCDown, and CV3 modules by incorporating CBAM and feature fusion techniques. These enhancements collectively boost the model's information utilization capacity and detection performance for small targets.

Installation & Dependencies:
bash

pip install -r requirements.txt

Training & Testing:
bash

python train.py

License & Citation:
Please cite our corresponding publication if you use AbaTND or YOLOv10-CBRC in your research.



The module names remain unchanged from their original implementation. Users may optionally modify these names according to their preferences, as such changes will not affect the model's accuracy or computational performance.

dataset:通过网盘分享的文件：AbaTND
"The AbaTND dataset is available via Baidu Netdisk:
Link: https://pan.baidu.com/s/12aF1maJM5DB_tBQK6XowUg
Access code: mycf"
