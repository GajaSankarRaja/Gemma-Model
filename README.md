QA Model with Google Gemma Base (QLoRA 32→4-bit)

This repository contains a Question-Answering (QA) model built on the Google Gemma Base model, fine-tuned using QLoRA (32→4-bit) for efficient inference. The project demonstrates instruction tuning, parameter-efficient fine-tuning, and end-to-end deployment.

Features

Instruction Tuning + PEFT: Optimized the model with Transformers using PEFT for efficient learning and minimal parameter updates.

Quantization: Reduced model weights from 32-bit to 4-bit for low-memory, high-speed inference.

Experiment Tracking: Monitored training and experiments using Weights & Biases (W&B).

Deployment: Hosted on Hugging Face Hub and made accessible via Gradio pipeline for interactive QA.

Data Handling: Leveraged Hugging Face Datasets for training and evaluation.

Tech Stack

Transformers
 – Model backbone and fine-tuning utilities

TRL
 – Training and reinforcement learning support

PEFT
 – Parameter-efficient fine-tuning

Gradio
 – Interactive web interface for model inference

W&B
 – Experiment tracking and visualization

Datasets
 – Data preprocessing and loading

Training Details

Environment: Google Colab

Training Duration: 8 hours

Workflow: Instruction-tuning → PEFT optimization → Quantization → W&B monitoring → Deployment


![Uploading image.png…]()
