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

**Evidence:** **15/18 SQL-question smoke checks (83.3%)** passed in a recorded 20-question benchmark using generated-SQL, result-presence and answer-keyword checks. This was not reference-result correctness or first-attempt accuracy. Historical retry counts are unreliable because the evaluator read the wrong trace field; the reported MRR improvement has no recovered reproducible aggregate.

[Repository](https://github.com/Venkateswara-Sahu/AI_Powered_Text-to-SQL_RAG_Chatbot) · [Live demo](https://huggingface.co/spaces/RiverStead/Text-to-SQL_RAG_Chatbot) · [Case study](https://venkateswara-sahu.vercel.app/#f1insightai)

### P&ID Intelligence — drawing-to-record prototype

Combined YOLOv8 symbol detection, targeted OCR, NetworkX spatial graph matching, and rule-based validation to produce reviewable equipment and instrumentation records.

**Evaluation:** Reduced OCR processing from **approximately 360 seconds to 7 seconds in one project benchmark**. The prototype flags low-confidence relationships for human review; it has not been evaluated on a representative industrial drawing corpus.

[Repository](https://github.com/Venkateswara-Sahu/P-ID-Processing-MTO-Extraction-System) · [Case study](https://venkateswara-sahu.vercel.app/#pid-intelligence)

### CTR Predictor — supporting tabular ML project

Engineered **150 features from 39 raw fields** across **10 million Criteo records**, tuned XGBoost and LightGBM with Optuna, and served scoring through Flask and Streamlit.

**Evidence boundary:** The serving code and released model assets are available. The README and dashboard disagree about the split labels for their displayed AUC values; numerical performance claims are omitted until the original evaluation artifacts are recovered. Training/serving preprocessing consistency also needs repair and validation.

[Repository](https://github.com/Venkateswara-Sahu/CTR_Predictor_and_Scorer) · [Live app](https://ctrpredictor.streamlit.app/) · [Case study](https://venkateswara-sahu.vercel.app/#ctr-predictor)

## Skills

- **Languages:** Python, SQL, Java, C/C++
- **Applied AI:** LangGraph, LangChain, RAG, FAISS, sentence-transformers, LLM APIs
- **Machine learning:** PyTorch, scikit-learn, XGBoost, LightGBM, Optuna
- **ML engineering:** FastAPI, Flask, Docker, GitHub Actions, Kafka, Airflow, MLflow
- **Data and vision:** SQL, TiDB Cloud, pandas, OpenCV, YOLOv8, Tesseract OCR, NetworkX

Based in Neelapalli, Andhra Pradesh. Open to **entry-level Applied AI, Machine Learning, and Generative AI roles**, relocation within India, and remote opportunities.
