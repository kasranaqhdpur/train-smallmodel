<div align="center">

[🇺🇸 English](README.md) | **🇮🇷 فارسی**

</div>
# 🤖 دستیار هوش مصنوعی فارسی

<div align="center">

### آموزش و Fine-tuning مدل **Google Gemma 2 2B** با استفاده از **QLoRA** برای مکالمات طبیعی فارسی

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![Transformers](https://img.shields.io/badge/🤗-Transformers-yellow)
![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)
![TRL](https://img.shields.io/badge/TRL-SFTTrainer-orange)
![License](https://img.shields.io/badge/License-Apache--2.0-red)

</div>

---

# 📖 معرفی پروژه

این مخزن شامل یک نوت‌بوک کامل برای **Fine-tuning مدل Google Gemma 2 2B** روی داده‌های مکالمه‌ای فارسی است.

در این پروژه تمام مراحل آموزش مدل از ابتدا تا انتها پیاده‌سازی شده است، از جمله:

- آماده‌سازی داده‌ها
- پیش‌پردازش
- Tokenization
- تنظیم LoRA و QLoRA
- آموزش مدل
- ارزیابی
- ذخیره Adapter
- تست و تولید پاسخ

هدف این پروژه ارائه یک نمونه کامل برای آموزش مدل‌های زبانی فارسی با استفاده از منابع سخت‌افزاری محدود است.

---

# ✨ امکانات

- 🚀 آموزش Gemma 2 2B
- ⚡ QLoRA (آموزش 4Bit)
- 🎯 LoRA Fine-tuning
- 🤗 Hugging Face Transformers
- 📚 Hugging Face Datasets
- 🔥 PEFT
- 🧠 TRL SFTTrainer
- 💬 دیتاست مکالمه‌ای فارسی
- 💾 ذخیره LoRA Adapter
- 🧪 تست و تولید پاسخ
- 📈 مناسب برای GPUهای محدود

---

# 📂 ساختار پروژه

```text
.
├── code.ipynb          # نوت‌بوک کامل آموزش
├── data.json           # نمونه‌ای از دیتاست
├── README.md
└── LICENSE
```

---

# 📚 دیتاست

دیتاست موجود در این مخزن تنها یک **نمونه کوچک** برای نمایش روند آموزش است.

## ⭐ نسخه کامل دیتاست

تمام دیتاست‌های کامل، مدل‌ها و بروزرسانی‌های آینده از طریق صفحه Hugging Face منتشر می‌شوند.

## 🤗 Hugging Face

### 🔗 https://huggingface.co/kasranaqhdpur

در صفحه Hugging Face می‌توانید به موارد زیر دسترسی داشته باشید:

- 📚 دیتاست‌های کامل فارسی
- 🤖 مدل‌های آموزش‌دیده
- 🧠 فایل‌های LoRA
- 📄 مستندات دیتاست
- 🚀 نسخه‌های جدید پروژه‌ها

---

# 🧠 فرمت دیتاست

نمونه داده‌ها به صورت مکالمه‌ای (ChatML) هستند.

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

# ⚙️ مراحل آموزش

```text
دیتاست
   │
   ▼
پیش‌پردازش
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
آموزش مدل
   │
   ▼
ارزیابی
   │
   ▼
ذخیره Adapter
   │
   ▼
تولید پاسخ
```

---

# 🚀 نصب

کلون کردن پروژه

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

cd YOUR_REPOSITORY
```

نصب کتابخانه‌ها

```bash
pip install -r requirements.txt
```

سپس فایل زیر را اجرا کنید:

```text
code.ipynb
```

تمام سلول‌ها را به ترتیب اجرا کنید.

---

# 🛠 تکنولوژی‌های استفاده شده

- Python
- PyTorch
- Transformers
- Datasets
- PEFT
- TRL
- Accelerate
- BitsAndBytes
- Google Gemma
- LoRA
- QLoRA

---

# 💻 سخت‌افزار پیشنهادی

| قطعه | پیشنهاد |
|-------|----------|
| GPU | RTX 3090 / L4 / A100 |
| حافظه گرافیکی | 16GB یا بیشتر |
| CUDA | نسخه 12 یا بالاتر |
| Python | نسخه 3.11 یا بالاتر |

---

# 📈 برنامه‌های آینده

- پشتیبانی از مکالمات چندمرحله‌ای
- بهبود پردازش متن فارسی
- اضافه شدن معیارهای ارزیابی
- خروجی GGUF
- پشتیبانی از Ollama
- پشتیبانی از Unsloth
- اتصال مستقیم به Hugging Face Hub
- توسعه دیتاست‌های جدید فارسی

---

# 🤗 منابع Hugging Face

تمام نسخه‌های کامل دیتاست‌ها، مدل‌ها و پروژه‌های آینده در صفحه زیر منتشر می‌شوند:

## 🔗 https://huggingface.co/kasranaqhdpur

در این صفحه می‌توانید به موارد زیر دسترسی داشته باشید:

- 📚 مجموعه دیتاست‌های فارسی
- 🤖 مدل‌های آموزش‌دیده
- 🧠 فایل‌های LoRA
- 📄 Dataset Card
- 🚀 پروژه‌های جدید

---

# ❤️ حمایت از پروژه

اگر این پروژه برای شما مفید بود، خوشحال می‌شوم با روش‌های زیر از آن حمایت کنید:

- ⭐ ستاره دادن به مخزن GitHub
- 🍴 Fork کردن پروژه
- 🤗 دنبال کردن صفحه Hugging Face
- 🐞 ثبت Issue
- 💡 ارسال Pull Request

حمایت شما باعث توسعه بیشتر پروژه‌های متن‌باز فارسی خواهد شد.

---

# 📄 مجوز

این پروژه تحت مجوز **Apache 2.0 License** منتشر شده است.

---

<div align="center">

### ❤️ ساخته شده برای جامعه هوش مصنوعی فارسی

**اگر این پروژه برایتان مفید بود، لطفاً به آن ⭐ بدهید.**

</div>
