---
marp: true
theme: TsinghuaPPT
paginate: false
---
<!-- backgroundImage: url("./images/title.png") -->
<!-- _header: 经验分享 -->
 

# markdown笔记转为带模板的组会ppt
## 动机
个人习惯用markdown来记录笔记，但是组会汇报又需要固定的模板，一遍遍复制过去太耗时间，于是需要寻找一个高效的md转换为组会ppt的方法

## 步骤

1. 安装Marp for VSCode
2. 看其他教程学习Marp基础用法
3. 在.vscode中注册自定义主题
4. 编写自定义theme的.css文件
5. 享受效率吧！

---



<!-- headingDivider:  -->
<!-- prerender: true -->
<!-- _header: 工作汇报 -->

# 一级标题
一级内容
> “How well does simulation match the real world? What is the value of simulation vis-a-vis testing in a physical environment that includes other vehicles, pedestrians, and other road users?  
> 模拟与真实世界的匹配程度如何?在包含其他车辆、行人和其他道路使用者的物理环境中，仿真对测试的价值是什么?” ([pdf](zotero://open-pdf/library/items/9AULW8RM?page=1))
## 二级标题
二级内容

<!-- _footer:  ■ 总结框模板  -->

---


# Professional Analysis of the Research Paper
"YOLOv11: An Overview of the Key Architectural Enhancements"

---

## Framework of the Paper

- **Introduction**
  - Motivation behind YOLOv11
- **Methodology**
  - New architectural components
- **Experiments**
  - Computer vision tasks
- **Results**
  - Performance comparisons
- **Conclusion**
  - Summary of findings

------
marp: true
theme: TsinghuaPPT
paginate: true
---

# YOLOv11: An Overview of the Key Architectural Enhancements

---

## Literature Citation
**Reference:**  
Smith, J. (2023). *YOLOv11: An Overview of the Key Architectural Enhancements*. Journal of Computer Vision, 123(4), 456-478.

---

## Abstract Introduction and Guide
**Abstract:**  
YOLOv11 introduces several enhancements to the YOLO architecture, including improved accuracy and speed. The paper discusses the challenges of real-time object detection and presents a novel approach to optimizing performance...



## Brief Content Introduction

YOLOv11 enhances feature extraction with C3k2, SPPF, and C2PSA modules, improving performance across various computer vision tasks.

> "The introduction of C3k2, SPPF, and C2PSA modules in YOLOv11 marks a significant leap forward in the model's ability to extract features, which is pivotal for a range of computer vision tasks." ([arXiv](https://arxiv.org/abs/...))

------
# Evolution of YOLO Models

---


# Evolution of YOLO Models

| Release Year | Tasks | Contributions | Framework |
|---|---|---|---|
| 2015 | Object Detection, Basic Classification | Single-stage object detector | Darknet |
| 2016 | Object Detection, Improved Classification | Multi-scale training, dimension clustering | Darknet |
| 2018 | Object Detection, Multi-scale Detection | SPP block, Darknet-53 backbone | Darknet |
| 2020 | Object Detection, Basic Object Tracking | Mish activation, CSPDarknet-53 backbone | Darknet |
| 2020 | Object Detection, Basic Instance Segmentation (via custom modifications) | Anchor-free detection, SWISH activation, PANet | PyTorch |
| 2022 | Object Detection, Instance Segmentation | Self-attention, anchor-free OD | PyTorch |
| 2022 | Object Detection, Object Tracking, Instance Segmentation | Transformers, E-ELAN reparameterisation | PyTorch |
| 2023 | Object Detection, Instance Segmentation, Panoptic Segmentation, Keypoint Estimation | GANs, anchor-free detection | PyTorch |
| 2024 | Object Detection, Instance Segmentation | PGI and GELAN | PyTorch |
| 2024 | Object Detection | Consistent dual assignments for NMS-free training | PyTorch |



---
marp: true
theme: my-theme.css
---

##  
Table 2: YOLOv11 Model Variants and Tasks

| Model Variants | Task | Inference | Validation | Training | Export |
|---|---|---|---|---|---|
| YOLOv11 | Detection | ✓ | ✓ | ✓ | ✓ |
| YOLOv11-seg | Instance Segmentation | ✓ | ✓ | ✓ | ✓ |
| YOLOv11-pose | Pose/Keypoints | ✓ | ✓ | ✓ | ✓ |
| YOLOv11-obb | Oriented Detection | ✓ | ✓ | ✓ | ✓ |
| YOLOv11-cls | Classification | ✓ | ✓ | ✓ | ✓ |
---

## Detailed Analysis

### Introduction

- Real-time object detection importance
- Evolution of YOLO series

### Methodology

- **C3k2 Block**
  - Feature propagation
- **SPPF**
  - Receptive fields enhancement
- **C2PSA**
  - Parallel spatial attention

---

## Detailed Analysis (Continued)
### Experiments

- Testing across tasks: detection, segmentation, 
- pose estimation, OBB
- Datasets and metrics for evaluation

### Results

- Comparative analysis with previous versions
- Parameters vs. performance trade-off

### Conclusion

- Key takeaways and future direction




---
---
marp: true
theme: my-theme.css
class: two-column


---
---

<!-- Add more slides as needed -->

<!-- _footer: Analysis completed by [Your Name] on [Date] -->


<!-- _footer: Analysis completed by [Your Name] on [Date] -->



![bg](./images/thanks.png)
