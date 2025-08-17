# Forest-Semantic-segmentation
Deforestation is a pressing global issue, contributing significantly to biodiversity loss, climate imbalance, and environmental degradation.

Traditional forest monitoring techniques, including manual surveys and conventional satellite image analysis, are limited by inefficiency, high cost, and susceptibility to human error.
With the advent of high-resolution aerial imagery and deeplearning techniques, automated forest segmentation has become a viable solution for large-scale ecological monitoring.

This project presents a comprehensive approach for forest semantic segmentation using three state-of-the-art deep learning models: U-Net, Fast U-Net, and DeepLabV3+ .

The models are trained and evaluated on annotated aerial imagery datasets consisting of forest and non-forest classes, with pixel-level accuracy.

U-Net employs a symmetric encoder-decoder structure with skip connections to enhance spatial resolution.

Fast U-Net is designed for real-time applications by reducing depth and complexity.

DeepLabV3+ utilizes atrous spatial pyramid pooling (ASPP) and a ResNet backbone to capture multiscale contextual information.

The performance of each model is assessed using the Intersection over Union (IoU) metric. 

Experimental results demonstrate that DeepLabV3+ achieves the highest segmentation accuracy, while Fast U-Net offers faster inference with acceptable performance trade-offs. The findings underscore the effectivenessof deep learning in forest cover classification and provide a foundation for future integration with multispectral data, explainable AI, and federated learning frameworks for scalable and intelligent environmental monitoring
# Results
## U-NET Inputs
<img width="1275" height="706" alt="image" src="https://github.com/user-attachments/assets/723340e9-82ba-476f-953c-dc9471d1f279" />

##  U-NET Outputs
<img width="1297" height="270" alt="image" src="https://github.com/user-attachments/assets/49b88d27-0458-43df-ba71-b78c31fa2750" />
 <img width="1260" height="276" alt="image" src="https://github.com/user-attachments/assets/0798d43d-0d50-4539-b48a-c731e7034e7b" />
 
## Fast U-Net Outputs
 <img width="1290" height="742" alt="image" src="https://github.com/user-attachments/assets/0a6e711e-65ab-4172-95af-974ab19c31cc" />
 
## DeepLab V3+ Outputs
<img width="1152" height="681" alt="image" src="https://github.com/user-attachments/assets/68cf070c-a1fb-42bc-b2a9-27bed68b5034" />




