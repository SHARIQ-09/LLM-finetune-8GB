# LLM-finetune-8GB
Instruction fine tuning on 8GB of GPU - Tinyllama
Prompt tuning of mistral 7b , llama3b - seperate notebboks

# Instruction Fine-Tuning on 8GB GPU

🚀 This repository demonstrates how to run **instruction fine-tuning** of a Large Language Model (LLM) on a **single 8GB GPU**.  
🚀 This repository demonstrates how to run **prompt fine-tuning** of a Large Language Model (LLM) - Mistrab 7B , LLama 3B on a **single 8GB GPU**
Most people assume you need 24–80GB cards for this task — this repo proves otherwise, with smart memory optimization techniques.  

---

## ✨ Key Highlights
- ✅ Instruction fine-tuning on **limited VRAM (8GB)**
- ✅ Prompt fine-tuning on **limited VRAM (8GB)**
- ✅ Avoiding OOM errors with **FP16 mixed precision**  
- ✅ Efficient batching & **gradient accumulation**  
- ✅ Layer freezing   
- ✅ End-to-end working Jupyter Notebook
- ✅ NO Lora used . 

---

## 📂 Contents
- `notebook.ipynb` → Full workflow for instruction fine-tuning
- prompt_fine_tuning = Mistral 7B
- prompt_fine_tuning_3b = Llama 3B
- Example dataset preprocessing  
- Training loop with mixed precision + scheduler  
- Evaluation with perplexity and predictions  

---

## ⚡ Requirements
- Python 3.10+  
- PyTorch with CUDA  
- Hugging Face `transformers`, `datasets`, `accelerate`  
- GPU: **NVIDIA 8GB VRAM (e.g., RTX 3060, 3070 laptop)**  

Install dependencies:
```bash
pip install -r requirements.txt

