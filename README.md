# Visual and Textual Prompts in VLLMs for Enhancing Emotion Recognition

**Authors:** Zhifeng Wang, Student Member, IEEE; Qixuan Zhang; Peter Zhang; Wenjia Niu; Kaihao Zhang; Ramesh Sankaranarayana; Sabrina Caldwell; Tom Gedeon, Senior Member, IEEE

---

## 📄 Abstract

Vision Large Language Models (VLLMs) exhibit promising potential for multi-modal understanding, yet their application to video-based emotion recognition remains limited by insufficient spatial and contextual awareness. Traditional approaches, which prioritize isolated facial features, often neglect critical non-verbal cues such as body language, environmental context, and social interactions, leading to reduced robustness in real-world scenarios. To address this gap, we propose **Set-of-Vision-Text Prompting (SoVTP)**, a novel framework that enhances zero-shot emotion recognition by integrating spatial annotations (e.g., bounding boxes, facial landmarks), physiological signals (facial action units), and contextual cues (body posture, scene dynamics, others’ emotions) into a unified prompting strategy. SoVTP preserves holistic scene information while enabling fine-grained analysis of facial muscle movements and interpersonal dynamics. Extensive experiments show that SoVTP achieves substantial improvements over existing visual prompting methods, demonstrating its effectiveness in enhancing VLLMs’ video emotion recognition capabilities.

---

## 📖 Overview

This repository provides all code and resources to reproduce the experiments and figures from our paper **“Visual and Textual Prompts in VLLMs for Enhancing Emotion Recognition.”** Our key idea is **Set-of-Vision-Text Prompting (SoVTP)**—a zero-shot multimodal prompting pipeline that overlays visual annotations and structured text prompts to guide a VLLM through:

1. **Spatial Annotations**: Bounding boxes, facial landmarks, and Action Units  
2. **Physiological Signals**: Facial muscle movements encoded via AUs  
3. **Contextual Cues**: Scene layout, objects, and activities  
4. **Social Signals**: Body posture, gestures, and expressions of nearby individuals  
