# Mauritania IMF Financial Analysis Using LLMs

## Project Overview
This project analyses the Mauritania IMF Country Report 2024 using Large Language Models (LLMs) to extract financial information, generate summaries, identify economic risks and create a financial dashboard.

## Models Used
- **Qwen2.5-7B-Instruct:** Summarisation, financial extraction and RAG answers.
- **Mistral-7B-Instruct-v0.3:** Evaluation of generated outputs.
- **all-MiniLM-L6-v2:** Text embeddings for FAISS retrieval.

## Technologies & libraries
Python, Google Colab, PyTorch, Transformers, FAISS, Sentence-Transformers, Pandas and Matplotlib.

## Main Features
- PDF text extraction and token-aware chunking.
- Eight section summaries and an executive summary.
- Financial indicator extraction in JSON format.
- Seven financial stability themes and economic risk analysis.
- Four economic trend series.
- FAISS-based Retrieval-Augmented Generation (RAG).
- LLM evaluation and human verification.
- High-resolution four-panel dashboard.

## How to Run
1. Open the notebook in Google Colab.
2. Enable a GPU runtime.
3. Run the cells sequentially.
4. Upload the Mauritania IMF 2024 PDF when prompted.


## Dataset
IMF Country Report No. 24/362 – Mauritania, 2024 Article IV Consultation.

