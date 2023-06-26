# Falcon7b-QLoRA
Notebook for fine tuning Falcon7b with QLoRA
Finetune Falcon-7b on a Google colab

Welcome to this Google Colab notebook that shows how to fine-tune the recent Falcon-7b model on a single Google colab and turn it into a chatbot

We will leverage PEFT library from Hugging Face ecosystem, as well as QLoRA for more memory efficient finetuning Setup

Run the cells below to setup and install the required libraries. For our experiment we will need accelerate, peft, transformers, datasets and TRL to leverage the recent SFTTrainer. We will use bitsandbytes to quantize the base model into 4bit. We will also install einops as it is a requirement to load Falcon models.
