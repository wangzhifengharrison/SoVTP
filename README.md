# Visual and Textual Prompts in VLLMs for Enhancing Emotion Recognition

**Authors:** Zhifeng Wang, Qixuan Zhang, Peter Zhang, Wenjia Niu, Kaihao Zhang, Ramesh Sankaranarayana, Sabrina Caldwell, Tom Gedeon  
**Venue:** *Journal of LaTeX Class Files, Vol. 18, No. 9, April 2025*

---

## 📖 Overview

This repository accompanies our paper **“Visual and Textual Prompts in VLLMs for Enhancing Emotion Recognition”**, in which we introduce **Set-of-Vision-Text Prompting (SoVTP)**, a zero-shot framework that significantly boosts video-based emotion recognition by integrating:

- **Spatial annotations** (bounding boxes, facial landmarks, Action Units)  
- **Physiological cues** (facial muscle movements via Action Units)  
- **Contextual information** (scene layout, objects, activities)  
- **Social signals** (body posture, gestures, others’ emotions)

SoVTP preserves holistic scene context while enabling fine-grained analysis of facial and non-verbal cues, leading to state-of-the-art performance with Vision Large Language Models (VLLMs).

---

## 🔑 Key Contributions

1. **Set-of-Vision-Text Prompting (SoVTP)**  
   A unified multimodal prompting strategy that overlays spatial and physiological annotations on full-frame inputs, avoiding information loss from cropping or masking.

2. **Multi-Stage Chain-of-Thought**  
   A five-stage textual prompting pipeline—(i) scene context, (ii) body language, (iii) others’ emotions, (iv) facial Action Units, (v) self-corrected final prediction—that structures VLLM reasoning and improves robustness.

3. **Extensive Zero-Shot Evaluation**  
   Demonstrated across Easy, Medium, and Hard tiers on real-world video benchmarks, SoVTP yields up to +16% Accuracy and +15% F1 gain over leading baselines.

4. **Ablation & Efficiency Trade-Offs**  
   Detailed ablation studies show the incremental value of each modality and quantify latency vs. accuracy trade-offs for real-time applications.

---

## 🛠️ Repository Structure

