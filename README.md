# Asif Pinjari

**AI Engineer, Agentic Systems & LLM Infrastructure**

I build the systems that sit between research-grade AI and production: agentic workflows that hold state across multi-step tasks, RAG pipelines that stay accurate under real-world document noise, and the evaluation tooling that makes autonomous agent behavior trustworthy enough to ship. My work spans both ends of that spectrum, from shipping LLM-powered services used by 200+ researchers and faculty, to academic research on agent reliability.

Based in Arizona. M.S. Computer Science, Northern Arizona University (3.9 GPA). IEEE-published author, PyPI package author, AWS Certified AI Practitioner.

[Portfolio](https://asifflix.vercel.app) · [LinkedIn](https://linkedin.com/in/asifp0209) · asifp0203@gmail.com

---

## What I work on

**Agentic systems.** Multi-agent orchestration where agents need to coordinate, hold shared state, and recover from failure, not just chain prompts. I care about the boundary conditions: what happens when an agent gets bad tool output, when a task needs to be re-planned mid-execution, or when one agent's output has to be trusted (or not) by another.

**RAG and retrieval at production scale.** Less interested in whether a demo answers one question correctly, and more in retrieval quality under real document noise, cost per query at scale, and where semantic search quietly fails.

**Agent evaluation.** Building benchmarks and evaluation harnesses that test agent behavior systematically rather than relying on a handful of manual spot checks.

**Token and cost efficiency.** Context pruning, prompt compression, and inference cost optimization. The unglamorous engineering work that decides whether an agentic system is actually deployable, or just a cool demo with a five-figure monthly API bill.

---

## Experience

**AI/ML Engineer, Northern Arizona University** *(Jan 2025 – Present)*
Design and deploy production AI systems for research teams across three departments: LLM applications on AWS Bedrock via LangChain, agentic workflows, and RAG pipelines for semantic search and document QA. Built end-to-end ML pipelines (ingestion, feature engineering, training, validation, packaging) that improved model accuracy by 30%, and FastAPI/Docker inference services that turned prototypes into deployed systems on AWS and GCP. Integrated LLM-powered analytics into enterprise campus systems, cutting manual data-gathering time by 40% for 200+ faculty and administrators.

**Research Assistant, AI Agents & Deep Learning, Northern Arizona University** *(Feb 2026 – Present)*
Building benchmark datasets and detection models for studying agent reliability under adversarial conditions, in collaboration with faculty advisors toward peer-reviewed publication. Includes designing a large-scale automated data generation pipeline on NAU's Monsoon HPC cluster and a transformer-based model for trajectory-level analysis.

**Teaching Assistant, Python & Deep Learning, Northern Arizona University** *(Feb 2026 – Present)*
Guide 100+ graduate students through implementing CNNs, RNNs, LSTMs, and Transformers in PyTorch and TensorFlow, including deployment to GCP. Mentor on software engineering standards, Git workflow, and reproducible ML experimentation.

**Smart Automation ML Engineer, Vincon Reality Pvt. Ltd.** *(Sep 2022 – May 2024)*
Built production intelligent-automation systems combining ML models (TensorFlow, XGBoost) with IoT device control, improving automation efficiency by 40%. Optimized models with TensorFlow Lite for edge deployment, hitting sub-50ms real-time inference across 10+ smart-home products.

---

## Publications & Credentials

**Human Activity Recognition, CNN+LSTM** · [IEEE InC4 2024](https://ieeexplore.ieee.org/document/10649335)
Designed a CNN+LSTM architecture to classify 15 human activities from time-series sensor data, reaching 92% accuracy on 1.2M+ sensor readings. Trained with PyTorch and GPU acceleration, using GridSearchCV for hyperparameter tuning.

**Open source:** [smart-preprocess-asif](https://github.com/Asif-0209/smart-preprocess-asif), a one-line data preprocessing toolkit published on PyPI.

**Certification:** AWS Certified AI Practitioner.

---

## Stack

**LLM / GenAI**
- LangChain, LlamaIndex, Amazon Bedrock, Claude API, OpenAI API, Hugging Face
- RAG, FAISS, embeddings, semantic search, LoRA/PEFT fine-tuning

**Agentic AI**
- Multi-agent orchestration, Model Context Protocol (MCP), LLM-as-judge
- Agent observability, tool use, n8n, Zapier

**ML / Deep Learning**
- PyTorch, TensorFlow, Scikit-learn, XGBoost
- CNNs, RNNs, LSTMs, Transformers, NLP, computer vision

**Data & Infra**
- Pandas, NumPy, Apache Spark, PostgreSQL, MongoDB
- AWS (Lambda, SageMaker, Bedrock, EC2, API Gateway), GCP
- Docker, Kubernetes, Terraform, MLflow, GitHub Actions

**Languages**
- Python, SQL, JavaScript, Bash
