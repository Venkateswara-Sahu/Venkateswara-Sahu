# Venkateswara Sahu

Applied AI and Machine Learning Engineer building evaluated AI systems, ML pipelines, and developer-facing tools.

[Portfolio](https://venkateswara-sahu.vercel.app/) · [Résumé](https://venkateswara-sahu.vercel.app/resumes/Venkateswara_Sahu_Applied_AI_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/venkateswara-sahu/) · [Email](mailto:venkateswarsahu000@gmail.com)

## Snapshot

- **2026 graduate:** B.Tech (Hons.) CSE — Data Science and Data Engineering, Lovely Professional University. **Aug 2022–Jun 2026 · CGPA 8.38/10.**
- **Completed Generative AI internship:** TransOrg Analytics (Pickl.AI) × LPU industry tie-up, **Jan–May 2026**. Led the technical implementation of F1InsightAI.
- **Package author:** Published [`vigil-drift`](https://pypi.org/project/vigil-drift/), with drift-monitoring code, automated tests, and reproducible baseline comparisons.

## Featured work

### Vigil — drift monitoring and evaluation

Published a Python package using adaptive and frozen autoencoders, reconstruction-error tests, and feature-level rankings. Added regression tests, GitHub Actions, and example Kafka ingestion and Airflow retraining workflows.

**Evaluation:** Compared **nine attribution ranking methods across 20 seeds and 24 conditions**: 18 synthetic and six controlled CICIDS2017 development-data conditions. Documented failure modes against statistical baselines; the study did **not** establish general superiority, held-out attack detection, or causal explanations.

[Repository](https://github.com/Venkateswara-Sahu/OWADD) · [PyPI package](https://pypi.org/project/vigil-drift/) · [Case study](https://venkateswara-sahu.vercel.app/#vigil)

### F1InsightAI — evaluated Text-to-SQL

Led the technical implementation of a **nine-node LangGraph workflow** with schema retrieval, SQL validation, and error-guided retries across **700,000+ Formula 1 records in 14 TiDB tables**, exposed through a Dockerized Flask API.

**October 2026 evaluation:** **39/40 first-attempt and 39/40 final reference-result matches** on a frozen 701,433-record snapshot, after 20 separate development queries. Independently labelled dense MRR@7 improved **0.678 → 0.888**. Five separate injected invalid-column probes recovered. This small authored F1 study uses related query patterns; it does not establish arbitrary-query accuracy or production readiness. [Protocol and raw results](https://github.com/Venkateswara-Sahu/AI_Powered_Text-to-SQL_RAG_Chatbot/blob/f627442cacb4ee9c3c0b504b0d5fa1ffebc539b5/docs/evaluation/results.md).

[Repository](https://github.com/Venkateswara-Sahu/AI_Powered_Text-to-SQL_RAG_Chatbot) · [Live demo](https://huggingface.co/spaces/RiverStead/Text-to-SQL_RAG_Chatbot) · [Case study](https://venkateswara-sahu.vercel.app/#f1insightai)

### P&ID Intelligence — drawing-to-record prototype

Combined YOLOv8 symbol detection, targeted OCR, NetworkX spatial graph matching, and rule-based validation to produce reviewable equipment and instrumentation records.

**Evaluation:** Reduced OCR processing from **approximately 360 seconds to 7 seconds in one project benchmark**. The prototype flags low-confidence relationships for human review; it has not been evaluated on a representative industrial drawing corpus.

[Repository](https://github.com/Venkateswara-Sahu/P-ID-Processing-MTO-Extraction-System) · [Case study](https://venkateswara-sahu.vercel.app/#pid-intelligence)

### CTR Predictor — supporting tabular ML project

Rebuilt the Criteo pipeline with **123 shared training/serving features** from 39 raw fields, training-only statistics and fold-excluded target encoding. Compared logistic regression, XGBoost and LightGBM; served the validation-selected model through Flask and Streamlit.

**Evidence:** The October 2026 bounded study measured **0.7605 ROC AUC** and **0.4857 log loss** on **249,987 held-out rows**, with raw predictions, baseline comparisons, checksums and row-bootstrap intervals. Historical preprocessing leaked labels, so its larger-run scores are not valid baselines. No causal ranking/revenue impact or production guarantee is claimed.

[Repository](https://github.com/Venkateswara-Sahu/CTR_Predictor_and_Scorer) · [Live app](https://ctrpredictor.streamlit.app/) · [Case study](https://venkateswara-sahu.vercel.app/#ctr-predictor)

## Skills

- **Languages:** Python, SQL, Java, C/C++
- **Applied AI:** LangGraph, LangChain, RAG, FAISS, sentence-transformers, LLM APIs
- **Machine learning:** PyTorch, scikit-learn, XGBoost, LightGBM, Optuna
- **ML engineering:** FastAPI, Flask, Docker, GitHub Actions, Kafka, Airflow, MLflow
- **Data and vision:** SQL, TiDB Cloud, pandas, OpenCV, YOLOv8, Tesseract OCR, NetworkX

Based in Neelapalli, Andhra Pradesh. Open to **entry-level Applied AI, Machine Learning, and Generative AI roles**, relocation within India, and remote opportunities.
