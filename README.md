# 🧠 Legal Contract Analyzer using Zero-Shot LLMs & Clause Risk Scoring

A smart legal document analyzer that leverages **Zero-Shot Large Language Model (LLM) inference** and **Semantic Embedding-based Clause Risk Scoring** to intelligently scan, analyze, and rate potential risks in contract clauses—**without requiring labeled training data**.

---

## 🚀 Key Features

- 🔍 **Clause Identification:** Automatically extracts and classifies contract clauses using LLM prompt engineering.
- 🧠 **Zero-Shot Risk Inference:** Uses pretrained LLMs (e.g., OpenAI GPT-4, Gemini, Mistral) to infer clause intent and risk *without prior examples*.
- 📊 **Semantic Risk Scoring:** Generates vector embeddings of clauses and computes similarity with high-risk legal clause patterns.
- ⚠️ **Risk-Based Alerts:** Flags suspicious or ambiguous language for legal review.
- 📁 **Colab-Ready Notebook:** Fully executable on Google Colab, no setup required.

---

## 🛠 Technologies Used

- Python (Colab)
- OpenAI GPT / Gemini API
- SentenceTransformers (SBERT)
- LangChain for LLM chaining
- FAISS / cosine similarity for embedding search
- Pandas / JSON parsing
- Matplotlib for clause visualization (optional)

---

## 📸 Demo Screenshots

### 🧾 1. Contract Clause Extraction + Risk Flag
![Clause Extraction](images/Legal%20Contract%20Analyzer.ipynb%20-%20Colab%20-%20Google%20Chrome%207_3_2025%209_37_45%20PM.png)

---

### 🤖 2. Zero-Shot LLM Evaluation of Clauses
![LLM Risk Evaluation](images/Legal%20Contract%20Analyzer.ipynb%20-%20Colab%20-%20Google%20Chrome%207_3_2025%209_38_17%20PM.png)

---

### 📉 3. Risk Score Interpretation with Color Indicators
![Risk Scores](images/Legal%20Contract%20Analyzer.ipynb%20-%20Colab%20-%20Google%20Chrome%207_3_2025%209_38_27%20PM.png)

---

## 📂 How It Works

1. **Upload** a legal contract (PDF/DOCX/Raw Text).
2. The system **splits it into clauses** and applies semantic parsing.
3. Each clause is sent through a **zero-shot prompt** to the LLM for risk classification.
4. Embedding similarity with high-risk clause corpus is computed to assign **risk scores**.
5. Results are **visualized** and flagged in a structured table.

---

## 🧪 Example Use Cases

- 📄 NDA clause analysis for compliance.
- 💼 Employment contract loophole detection.
- 🤝 Partnership agreements risk grading.
- 🧾 Lease agreement risk redlining.

---

## 📌 To Do (Future Scope)

- 🧠 Fine-tune on domain-specific contracts (e.g., healthcare, IP, SaaS).
- 📊 Interactive dashboard for contract exploration.
- 🤖 Integrate OCR for scanned documents.
- 🔒 Add explainability using LLM-generated rationale.

---

## 💬 Citation

> Developed by Sudharsan S — leveraging open-source NLP and zero-shot LLM inference for legal automation.

---

## 🌐 License

This project is open-source and licensed under the MIT License.
