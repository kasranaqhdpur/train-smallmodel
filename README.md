<div align="center">

🇺🇸 **English** | [🇩🇪 Deutsch](READMEde.md) | [🇮🇷 فارسی](READMEfa.md)

</div>

# 🤖 Persian Companion AI

<p align="center">

Fine-tuning <b>Google Gemma 2 2B</b> for Natural Persian Conversations using <b>QLoRA</b>, <b>LoRA</b>, and the Hugging Face ecosystem.

</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![Transformers](https://img.shields.io/badge/🤗-Transformers-yellow)
![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)
![TRL](https://img.shields.io/badge/TRL-SFTTrainer-orange)
![License](https://img.shields.io/badge/License-Apache--2.0-red)

</p>

---

# 📖 Overview

This repository contains a complete notebook for fine-tuning **Google Gemma 2 2B** on Persian conversational data using **QLoRA**.

The project demonstrates an end-to-end training pipeline, from dataset preprocessing to model training, evaluation, inference, and saving LoRA adapters.

It is designed for developers, researchers, and AI enthusiasts who want to build lightweight Persian Large Language Models with limited GPU resources.

---

# ✨ Features

- 🚀 Google Gemma 2 2B
- ⚡ QLoRA (4-bit Quantization)
- 🎯 LoRA Fine-tuning
- 🤗 Hugging Face Transformers
- 📚 Hugging Face Datasets
- 🔥 PEFT
- 🧠 TRL SFTTrainer
- 💬 Persian Conversational Dataset
- 💾 Save & Load LoRA Adapters
- 🧪 Inference Examples
- 📈 GPU Efficient Training

---

# 📂 Project Structure

```
.
├── code.ipynb          # Complete training notebook
├── data.json           # Example dataset
├── README.md
└── LICENSE
```

---

# 📚 Dataset

The dataset included in this repository is a **small example** used to demonstrate the training pipeline.

## ⭐ Full Dataset

The **complete Persian datasets**, future updates, and additional AI resources are available on my Hugging Face profile.

## 🤗 Hugging Face

> **https://huggingface.co/kasranaqhdpur**

There you can find:

- 📚 Complete Persian Datasets
- 🤖 Fine-tuned Models
- 🧠 LoRA Checkpoints
- 📄 Dataset Documentation
- 🚀 Future Releases

---

# 🧠 Dataset Format

The project uses conversational training samples following the ChatML format.

```json
{
  "messages": [
    {
      "role": "system",
      "content": "..."
    },
    {
      "role": "user",
      "content": "..."
    },
    {
      "role": "assistant",
      "content": "..."
    }
  ]
}
```

---

# ⚙️ Training Pipeline

```
Dataset
   │
   ▼
Preprocessing
   │
   ▼
Tokenizer
   │
   ▼
QLoRA
   │
   ▼
SFTTrainer
   │
   ▼
Training
   │
   ▼
Evaluation
   │
   ▼
Save Adapter
   │
   ▼
Inference
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

cd YOUR_REPOSITORY
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open

```
code.ipynb
```

Run each notebook cell in order.

---

# 🛠 Technologies

- Python
- PyTorch
- Transformers
- Datasets
- PEFT
- TRL
- Accelerate
- BitsAndBytes
- Gemma 2
- LoRA
- QLoRA

---

# 💻 Hardware

Recommended

| Component | Recommendation |
|------------|---------------|
| GPU | NVIDIA RTX 3090 / A100 / L4 |
| VRAM | 16GB+ |
| CUDA | 12.x |
| Python | 3.11+ |

---

# 📈 Future Improvements

- Multi-turn conversations
- Better Persian normalization
- Evaluation metrics
- GGUF Export
- Ollama Support
- Unsloth Integration
- RAG Support
- Hugging Face Hub Upload

---

# 🤗 Hugging Face Resources

For the latest datasets, models, and future updates, visit:

### 🔗 https://huggingface.co/kasranaqhdpur

Available resources include:

- Persian Datasets
- AI Models
- LoRA Adapters
- Dataset Cards
- Training Resources

---

# ❤️ Support

If you find this project useful, please consider:

- ⭐ Starring this repository
- 🍴 Forking the project
- 🤗 Following my Hugging Face profile
- 🐞 Opening an issue
- 💡 Contributing improvements

Every star helps the project reach more developers.

---

# 📄 License

This project is licensed under the Apache 2.0 License.

---

<p align="center">

Made with ❤️ for the Persian AI Community

**⭐ Don't forget to Star the repository if you found it useful!**

</p>
