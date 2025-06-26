# Hugging-Face Object Detection by YOLOS

[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-3B4252?style=flat&logo=huggingface&logoColor=)](https://huggingface.co/)
![Static Badge](https://img.shields.io/badge/Object-Detection-cyan)
![Static Badge](https://img.shields.io/badge/YOLOS-8A2BE2)

Object Detection for the caps of marker pens using **YOLOS** Deep Learning Algorithm in **Hugging Face**.

## Dataset
- Marker Pens' Caps (Custom)

Annotation Type - Bounding Boxes

Class &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &ensp; - CAP

## Methodology
![Hugging Face](https://img.shields.io/badge/-HuggingFace-yellow?style=for-the-badge&logo=HuggingFace&logoColor=black&logoHeight=20)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

- `"hustvl/yolos-small"` Model
- Used pytorch_lightning, epochs=10
- Used coco_evaluator for evaluation

## Results
- ### Evaluation of trained model

Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = `0.684`

Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = `0.783`

---
⭐ Example Images results in `YOLOS_Huggingface_det.ipynb`
