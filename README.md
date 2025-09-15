# 📝 Hybrid Text Summarizer with GPT-2 Medium

✨ **Stable · Deterministic · Reproducible** ✨  
This project implements a hybrid text summarization pipeline combining **extractive** and **abstractive** methods.  
It uses **GPT-2 Medium** to generate deterministic, reproducible summaries that balance factual reliability with natural language fluency.  

---

## 🚀 Key Features
- 📌 **Hybrid pipeline** → Extractive bullets + Abstractive paragraph  
- 🎯 **Deterministic output** → `do_sample=False` ensures the same result every run  
- 🧹 **Clean preprocessing** → Removes emails, URLs, and noisy text  
- ⚡ **Lightweight & portable** → Runs on Google Colab (free GPU) or local CUDA workstation  
- 🧑‍🔬 **Research-oriented design** → Highlights explainability, efficiency, and reproducibility in modern NLP  

---

## 📦 Installation
```bash
pip install -r requirements.txt

Dependencies:

transformers==4.44.2

accelerate==0.34.2

nltk==3.9.1

▶️ Usage

Open and run the Jupyter notebook summarizer.ipynb
.
It will:

Load a .txt file

Apply preprocessing

Generate BULLETS (extractive summary)

Generate PARAGRAPH (abstractive summary with GPT-2 Medium)

Output is clean, factual, and reproducible.

📚 Example Output

BULLETS:
- From healthcare to finance and transportation, AI systems are being used to analyze massive datasets, recognize complex patterns, and assist humans in making critical decisions.
- Breakthroughs in deep learning and natural language processing have led to impressive advances in image recognition, speech synthesis, and text generation.
- Modern AI faces three major challenges: explainability, efficiency, and security.
- Efficiency focuses on reducing computational costs through model compression, pruning, and quantization so that AI can run effectively even on limited hardware.

PARAGRAPH:
From healthcare to finance and transportation, AI systems are being used to analyze massive datasets, recognize complex patterns, and assist humans in making critical decisions. Modern AI faces three major challenges: explainability, efficiency, and security. Efficiency focuses on reducing computational costs through model compression, pruning, and quantization so that AI can run effectively even on limited hardware. Security involves defending models against adversarial attacks, data poisoning, and distribution shifts that could degrade performance in real-world environments.


🔮 Future Work

🧠 Integration with GPT-Neo for more robust generation

🌍 Multi-language summarization (including Turkish)

⚡ Model optimization with ONNX and quantization

📜 License

MIT License © 2025


