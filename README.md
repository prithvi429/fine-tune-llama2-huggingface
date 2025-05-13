# fine-tune-llama2-huggingface
A hands-on notebook for fine-tuning Meta’s LLaMA 2 model using Hugging Face tools, PEFT strategies (LoRA), and custom training data.


# 🦙 Fine-Tune LLaMA 2 with Hugging Face & PEFT

This project provides a hands-on Jupyter Notebook that demonstrates how to fine-tune **Meta's LLaMA 2 model** using Hugging Face's `transformers`, `datasets`, and `PEFT` (Parameter-Efficient Fine-Tuning) libraries.

It is designed for researchers, developers, and AI practitioners who want to adapt LLaMA 2 to domain-specific tasks with minimal computational resources.

---

## 🚀 Features

- ✅ Fine-tune LLaMA 2 using **LoRA** via Hugging Face PEFT
- ✅ Load and preprocess custom datasets with `datasets`
- ✅ Save and evaluate the fine-tuned model
- ✅ Easily extensible for different NLP tasks (Q&A, chat, classification, etc.)

---

## 📁 Project Structure

llama2-fine-tuning/
├── Fine_tune_Llama_2.ipynb # Main notebook with training pipeline
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies (optional)


---

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt

manually install core dependencies:
pip install transformers datasets peft accelerate

 also need:
pip install bitsandbytes scipy
