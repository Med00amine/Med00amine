# Mohamed Amine Bouzoffara

### AI / Machine Learning Engineer · Researcher

I work at the intersection of **machine learning research and engineering**.

My current interests are centered on building learning systems that remain useful under
real-world constraints: incomplete data, distributed environments, limited information,
and the gap between experimental models and deployable systems.

My recent research has focused on **missing-data mechanisms (MCAR, MAR, MNAR)**,
imputation strategies, and **federated learning under incomplete data**. Alongside
research, I build practical ML systems using PyTorch, NLP, APIs, containers, and cloud
infrastructure.

I am particularly interested in the questions that appear after a model works in a
notebook:

> How does it behave when the data is incomplete?  
> What happens when the training process is distributed?  
> Can the model be evaluated properly?  
> And can the resulting system actually be deployed?

---

## Research

My current research interests include:

- Federated Learning
- Distributed Machine Learning
- Learning with Missing Data
- MCAR / MAR / MNAR mechanisms
- Imputation and incomplete-data modeling
- Robust Machine Learning
- Deep Learning
- Natural Language Processing
- Model evaluation and reliability

I am interested in research that is experimentally rigorous but remains connected to
practical machine learning systems.

---

## Selected Work

### Federated Learning under Missing Data

A PyTorch-based distributed learning system investigating the effect of missing data on
federated training.

**Focus:**

- MNAR data generation
- Imputation strategies
- Federated optimization
- Centralized vs distributed learning
- Model robustness under incomplete observations

---

### Arabic NLP with Transformers

Fine-tuned transformer models for Arabic text classification, including preprocessing,
tokenization and contextual embeddings.

**Result:** 95% classification accuracy on the evaluated dataset.

---

### Time-Series Anomaly Detection

A deep learning pipeline for detecting anomalies in fraud-related time-series data.

The system experiments with encoder-based and CNN architectures and exposes the trained
model through a **FastAPI REST service**, packaged with Docker.

---

## Engineering

I enjoy working across the complete ML lifecycle:

```text
Data
  ↓
Exploration & Analysis
  ↓
Feature Engineering
  ↓
Model Development
  ↓
Evaluation
  ↓
Experiment Tracking
  ↓
API / Service
  ↓
Containerization
  ↓
Cloud Deployment
