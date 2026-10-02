# Smart Baby Monitor Using Vision-Language Models (VLMs)

**Team Members**

Drishti Jaiswal

Ankitha Rajesh

Sara Sorokina

Eric Xu

**Motivation**

Traditional baby monitors require parents to continuously watch or listen to their baby. Vision-Language Models (VLMs) can analyze images and generate natural-language descriptions, making them useful for automatically recognizing and reporting common baby activities.

Our project will explore how effectively pretrained VLMs can recognize activities such as sleeping, playing, and being awake. We will also investigate how different prompting strategies affect classification accuracy.

**Design Goals**

Use a pretrained VLM to recognize common baby activities.

Compare different prompting strategies and their accuracy.

Generate short natural-language descriptions of detected activities.

Explore audio-based crying detection.

Implement a simple alert system for events such as crying.

**Deliverables**

Working VLM image-analysis pipeline.

* Baby activity classification.

* Natural-language activity summaries.

* Comparison of different prompting strategies.

* Optional audio crying detection and alert system.

* Final demonstration, report, and presentation.

**System Blocks**

Image / Video
      → 
Preprocessing
      → 
Vision-Language Model
      → 
Activity Classification
      → 
Natural-Language Summary
      → 
Alert System

**Optional audio component:**

Audio → Audio Model → Cry Detection → Alert System

**Hardware / Software Requirements**

**Hardware**

* Laptop

* CUDA-enabled GPU or Google Colab

* Optional microphone/webcam

* Software

* Python

* PyTorch

* Hugging Face Transformers

* OpenCV

* Git/GitHub

**Team Responsibilities**

**Drishti Jaiswal — Software & Research Lead**

Develop the VLM pipeline and activity recognition components.

Research VLM models, datasets, and related approaches.

Assist with testing and evaluation.

**Ankitha Rajesh — Software & Setup Lead**

Develop the VLM pipeline and help integrate the model.

Set up the development environment and required software.

Assist with testing and debugging.

**Sara Sorokina — Algorithm Design & Writing Lead**

Design and compare different prompting strategies.

Develop the evaluation approach and analyze results.

Help write project documentation and the final report.

**Eric Xu — Networking & Audio Integration Lead**

Develop the audio/cry-detection component.

Integrate the visual and audio components.

Develop the alert mechanism and assist with system testing.

All team members will contribute to software development, experimentation, testing, documentation, and the final presentation.

**Project Timeline**

Phase 1: Research, GitHub setup, and model selection
Phase 2: Implement basic VLM pipeline
Phase 3: Test prompting strategies and evaluate accuracy
Phase 4: Add audio detection and alert system
Phase 5: Final testing, documentation, and presentation

**References**

Hugging Face LLaVA Documentation: https://huggingface.co/docs/transformers/main/en/model_doc/llava

VLM and Multimodal Reasoning Paper: https://arxiv.org/abs/2306.14895

Visual Instruction Tuning (LLaVA): https://arxiv.org/abs/2304.08485
