#  Speech to Reasoning using Whisper + Unsloth (4-bit)

This repository contains **Task 4** of my Generative AI internship (Month 2).

The goal of this task is to build an **end-to-end speech-to-reasoning pipeline** using:
- OpenAI Whisper for speech-to-text
- Unsloth dynamic 4-bit quantized LLM for reasoning
- Google Colab with a T4 GPU

---

## 🚀 What This Project Does

1. Takes an **audio file** as input  
2. Converts speech → text using **Whisper**
3. Sends the transcribed text to a **4-bit quantized LLM**
4. Generates a **reasoned, grounded response**

This demonstrates how speech understanding can be connected directly to large language model reasoning.

---

## 🧠 Models & Tools Used

- **Whisper (base)** — speech-to-text transcription  
- **Unsloth Mistral 7B Instruct (4-bit)** — reasoning model  
- **Google Colab (T4 GPU)**  
- **PyTorch + Transformers**

---


---

## ⚙️ How It Works (High Level)

1. GPU is enabled on Google Colab  
2. Whisper transcribes a sample audio file  
3. The transcription is passed into a quantized LLM  
4. The model generates a concise summary of the audio content  

---

## ✅ Key Outcomes

- Successfully ran Whisper on GPU
- Loaded a 4-bit quantized LLM using Unsloth
- Connected speech → reasoning without crashes
- Handled real-world issues like audio format errors and dependency warnings

---

## 📝 Notes

- The notebook is designed to be **clean and reproducible**
- Warnings related to Torch versions on Colab were handled safely
- The focus is on **inference**, not training

---

## 👤 Author

**Sallam**  
Generative AI Intern  

## 📁 File Structure

