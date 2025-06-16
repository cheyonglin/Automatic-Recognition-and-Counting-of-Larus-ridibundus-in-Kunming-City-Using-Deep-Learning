# Automatic Recognition and Counting of Larus ridibundus in Kunming Using Deep Learning

Yonglin Che, Xiaolong Xie, Rong Guo, Yucheng Zeng, Jiajin Zhang

# Description

This repository contains the code for the framework used in this study, which is a method for automated tracking and counting of *L. ridibundus*.

Please refer to the ["Documentation"](https://alexhang212.github.io/YOLO_Behaviour_Repo/) for full installation and implementation guidelines, and the [paper](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.14502) for detailed description of the method!

![image-20250616221811532](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20250616221811532.png)



## Abstract

The Larus ridibundus (L.ridibundus), a prominent part of Kunming's landscape, attracts many tourists and boosts the local tourism industry. Effective population monitoring of this species matters for wetland environment evaluation, biodiversity conservation, and ecological civilization construction. Currently, L.ridibundus population statistics mainly rely on manual methods, which are labor-intensive and inefficient. To overcome these limits, we propose a deep learning (DL) framework. It automatically recognizes and counts L.ridibundus by combining CDSP2-YOLOv8n with DeepSORT, aiming to efficiently monitor their population metrics. Our framework uses the optimized YOLOv8n model to achieve excellent multi-object detection for this species. It also uses DeepSORT to effectively reduce target loss from occlusion or overlap during the birds' flight, providing a sophisticated DL approach for population monitoring. Experimental results show the modified CDSP2-YOLOv8n model works well on the collected L.ridibundus multi-object detection dataset. Its mAP@0.5, mAP@0.5:0.95, Precision, and Recall reach 0.9705, 0.6557, 0.9685, and 0.9496 respectively. Also, combining with DeepSORT, the tracking accuracy for L.ridibundus is 89.7%, with precision at 83.5%. Compared to manual counting, our framework has an average accuracy of 91.58%, greatly enhancing the efficiency and accuracy of L.ridibundus population monitoring. In conclusion, we've successfully realized automatic identification and counting of L.ridibundus. This method accurately identifies and stably tracks L.ridibundus, and effectively counts its population. It breaks traditional manual monitoring limits, providing a novel and comprehensive technical means for L.ridibundus monitoring and protection, with high robustness and application value.

# Quick Start

Before running the project, it is necessary to set up the appropriate environment. The specific steps are as follows:

```
conda create -n SY python=3.8
conda activate SY

pip install -r requirements.txt
```

## Run Inference on sample data

After setting up the environment, run `System_GUI.py` directly to launch the program and test the sample video.

![image-20250616223941051](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20250616223941051.png)

## Contact

If you have any questions/ suggestions with the pipeline, or any additional instructions/ guidelines you would like to see in the documentation, feel free to leave a git issue or shoot me an email!

