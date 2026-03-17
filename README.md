# Simple Baselines for Few-Shot Fine-Grained Recognition

## Overview
This project explores whether modern pretrained models (DINOv2, CLIP, ViT) combined with simple classifiers can outperform complex meta-learning methods in few-shot fine-grained image classification.

## Key Results
- 98.85% accuracy on CUB-200-2011 (5-shot)
- 99.97% accuracy on Oxford Flowers-102 (5-shot)
- 82.92% accuracy on FGVC-Aircraft (5-shot)
- Outperforms meta-learning methods like ProtoNet and FEAT by ~10%

## Method
- Frozen pretrained feature extractors:
  - DINOv2
  - CLIP
  - ViT-B/16
  - ResNet-50
- Simple classifiers:
  - Logistic Regression
  - Nearest Class Centroid
  - k-NN

No task-specific training was used.

## Paper
📄 Read the full paper

## Why This Matters
This work shows that representation quality is more important than complex learning algorithms for few-shot tasks.

