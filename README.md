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

## Project Timeline

### Week 1: Research, Setup, and Model Selection
- Learn the basics of Vision-Language Models (VLMs).
- Research pretrained VLMs such as LLaVA.
- Select the VLM and activity categories for the project.
- Identify and prepare an appropriate dataset.
- Set up the Python, PyTorch, and Hugging Face environment.
- Create and organize the project GitHub repository.

### Week 2: Basic VLM Pipeline
- Implement the basic image preprocessing pipeline.
- Load the selected pretrained VLM.
- Pass baby images to the VLM with appropriate prompts.
- Generate activity classifications such as sleeping, awake, and playing.
- Generate short natural-language descriptions of the detected activity.
- Demonstrate the first working version of the VLM pipeline.

### Week 3: Activity Recognition and Evaluation Setup
- Finalize the activity categories and test dataset.
- Organize and label the evaluation data.
- Develop an automated evaluation pipeline.
- Ensure that VLM outputs can be consistently interpreted as activity classifications.
- Establish evaluation metrics such as overall and per-activity accuracy.

### Week 4: Prompting Experiments
- Design and test different prompting strategies.
- Run the prompts on the same evaluation dataset.
- Compare the activity predictions produced by each prompting strategy.
- Record classification results and errors.
- Identify how prompt design affects activity-recognition accuracy.

### Week 5: Evaluation and Analysis
- Calculate overall and per-activity accuracy.
- Generate confusion matrices and other visualizations.
- Analyze correct and incorrect predictions.
- Measure VLM inference latency.
- Summarize the results of the prompting experiments.
- Finalize the main experimental results.

### Week 6: Audio and Alerting Extension
- Implement optional audio-based crying detection.
- Process audio input using an appropriate audio model.
- Integrate audio-based crying detection with the visual VLM pipeline.
- Implement a simple alert mechanism for detected crying.
- Test the integrated system under different conditions.

### Week 7: Final Integration and Presentation
- Perform final system testing and debugging.
- Finalize the VLM and optional audio components.
- Organize experimental results and figures.
- Clean and document the GitHub repository.
- Complete the final report.
- Prepare the final presentation and demonstration.
**References**

Hugging Face LLaVA Documentation: https://huggingface.co/docs/transformers/main/en/model_doc/llava

VLM and Multimodal Reasoning Paper: https://arxiv.org/abs/2306.14895

Visual Instruction Tuning (LLaVA): https://arxiv.org/abs/2304.08485
