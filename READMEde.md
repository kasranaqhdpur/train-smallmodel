<div align="center">

[🇺🇸 English](README.md) | 🇩🇪 **Deutsch** | [🇮🇷 فارسی](READMEfa.md)

</div>

# 🤖 Persian Companion AI

<div align="center">

### Feinabstimmung von **Google Gemma 2 2B** mit **QLoRA** für natürliche persische Konversationen

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![Transformers](https://img.shields.io/badge/🤗-Transformers-yellow)
![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)
![TRL](https://img.shields.io/badge/TRL-SFTTrainer-orange)
![License](https://img.shields.io/badge/License-Apache--2.0-red)

</div>

---

# 📖 Überblick

Dieses Repository enthält ein vollständiges Notebook zur Feinabstimmung von **Google Gemma 2 2B** mit persischen Konversationsdaten unter Verwendung von **QLoRA**.

Das Projekt zeigt den gesamten Trainingsablauf – von der Datenvorbereitung über das Training bis hin zur Auswertung und Inferenz.

Es richtet sich an Entwickler, Forschende und KI-Enthusiasten, die leistungsfähige persische Sprachmodelle mit begrenzten GPU-Ressourcen trainieren möchten.

---

# ✨ Funktionen

- 🚀 Google Gemma 2 2B
- ⚡ QLoRA (4-Bit Quantisierung)
- 🎯 LoRA Fine-Tuning
- 🤗 Hugging Face Transformers
- 📚 Hugging Face Datasets
- 🔥 PEFT
- 🧠 TRL SFTTrainer
- 💬 Persischer Konversationsdatensatz
- 💾 Speichern von LoRA-Adaptern
- 🧪 Inferenz-Beispiele
- 📈 Effizientes GPU-Training

---

# 📂 Projektstruktur

```text
.
├── code.ipynb          # Vollständiges Trainings-Notebook
├── data.json           # Beispiel-Datensatz
├── README.md
├── README.de.md
├── README.fa.md
└── LICENSE
```

---

# 📚 Datensatz

Der in diesem Repository enthaltene Datensatz ist lediglich ein **kleines Beispiel**, um den Trainingsprozess zu demonstrieren.

## 🤗 Vollständiger Datensatz

Die vollständigen Datensätze, trainierten Modelle und zukünftigen Updates sind auf meinem Hugging Face-Profil verfügbar.

### 🔗 https://huggingface.co/kasranaqhdpur

Dort finden Sie:

- 📚 Vollständige persische Datensätze
- 🤖 Feinabgestimmte Modelle
- 🧠 LoRA-Checkpoints
- 📄 Datensatz-Dokumentationen
- 🚀 Zukünftige Veröffentlichungen

---

# 🧠 Datensatzformat

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

# ⚙️ Trainingsablauf

```text
Datensatz
    │
    ▼
Vorverarbeitung
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
LoRA speichern
    │
    ▼
Inferenz
```

---

# 🚀 Installation

Repository klonen

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

cd YOUR_REPOSITORY
```

Abhängigkeiten installieren

```bash
pip install -r requirements.txt
```

Öffnen Sie anschließend:

```text
code.ipynb
```

Führen Sie alle Notebook-Zellen der Reihe nach aus.

---

# 🛠 Verwendete Technologien

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

# 💻 Empfohlene Hardware

| Komponente | Empfehlung |
|------------|------------|
| GPU | RTX 3090 / L4 / A100 |
| VRAM | 16 GB oder mehr |
| CUDA | Version 12 oder höher |
| Python | Version 3.11 oder höher |

---

# 📈 Zukünftige Verbesserungen

- Mehrstufige Konversationen
- Verbesserte persische Textnormalisierung
- Bewertungsmetriken
- GGUF-Export
- Ollama-Unterstützung
- Unsloth-Integration
- Hugging Face Hub
- Neue persische Datensätze

---

# 🤗 Hugging Face

Alle vollständigen Datensätze, Modelle und zukünftigen Veröffentlichungen finden Sie unter:

## https://huggingface.co/kasranaqhdpur

---

# ❤️ Mitwirken

Wenn Ihnen dieses Projekt gefällt, können Sie es unterstützen durch:

- ⭐ Einen Stern auf GitHub
- 🍴 Einen Fork des Projekts
- 🤗 Folgen meines Hugging Face-Profils
- 🐞 Issues melden
- 💡 Pull Requests einreichen

---

# 📄 Lizenz

Dieses Projekt steht unter der **Apache License 2.0**.

---

<div align="center">

### ❤️ Entwickelt für die persische KI-Community

**Wenn Ihnen dieses Projekt gefällt, geben Sie ihm gerne einen ⭐ auf GitHub!**

</div>
