# 📊 Data Science Mastery Roadmap

An interactive, self-contained web roadmap for learning data science from the ground up — structured across 3 phases, 18 weeks, and 126 daily lessons, with curated resources, hands-on exercises, and weekend projects at every step.

🔗 **Live site:** https://r123-rb.github.io/data-science-roadmap/

---

## What This Is

This is a single-file HTML page that lays out a complete, opinionated curriculum for becoming a professional data scientist. It is not a collection of links or a vague list of topics — every day of every week has a concrete topic, a set of specific concepts to learn, hand-picked learning resources, and a practical coding exercise to reinforce the material.

The roadmap was designed to be followed sequentially, but it can also be used as a reference to fill gaps in any specific area. No installation, no login, and no internet connection required after the page loads — just open `index.html` in any browser.

---

## Curriculum Overview

The curriculum is organized into **4 phases** and **18 weeks**.

### Phase 1 — Foundations (Weeks 1–5)
Build the core toolkit every data scientist uses daily.

| Week | Title | Topics |
|------|-------|--------|
| 1 | Python for Data Science | Data types, control flow, functions, OOP, file I/O |
| 2 | NumPy & Pandas | Arrays, broadcasting, DataFrames, GroupBy, time series, Matplotlib, Seaborn |
| 3 | Statistics & Probability | Distributions, hypothesis testing, Bayesian inference, regression diagnostics |
| 4 | Math for ML | Linear algebra (SVD, eigendecomposition), multivariate calculus, optimization, information theory |
| 5 | Data Wrangling & SQL | SQL (joins, window functions, CTEs), Python–database integration, APIs, Parquet, data formats |

### Phase 2 — Machine Learning (Weeks 6–9)
Go from classical ML concepts.

| Week | Title | Topics |
|------|-------|--------|
| 6 | ML Foundations & Linear Models | sklearn workflow, linear/logistic regression, evaluation metrics, regularization, feature engineering |
| 7 | Tree-Based Models & Tuning | Decision trees, random forests, XGBoost, LightGBM, CatBoost, Optuna, cross-validation |
| 8 | Unsupervised Learning | K-Means, DBSCAN, PCA, t-SNE, UMAP, anomaly detection, association rules |
| 9 | SVMs & Time Series | SVM, Naive Bayes, kNN, ARIMA, Prophet, LSTM forecasting, feature-based forecasting |

### Phase 3 — Deep Learning (Weeks 9–14)
Deep learning to generative AI and reinforcement learning.

| Week | Title | Topics |
|------|-------|--------|
| 10 | Deep Learning Foundations | PyTorch, neural networks, backprop, CNNs, batch norm, dropout, learning rate schedulers |
| 11 | Computer Vision | CNN architectures (ResNet, EfficientNet), transfer learning, augmentation, object detection, ViT |
| 12 | NLP & Text | spaCy, TF-IDF, Word2Vec, LSTMs, Transformers, Hugging Face fine-tuning |
| 13 | Generative AI & LLMs | LLM inference, prompt engineering, RAG, fine-tuning (QLoRA), LangChain agents, diffusion models |
| 14 | Reinforcement Learning | MDPs, Q-learning, DQN, PPO, multi-armed bandits, RLHF, Gymnasium, stable-baselines3 |

### Phase 4 — Production & Career (Weeks 15–18)
Ship real systems and land the job.

| Week | Title | Topics |
|------|-------|--------|
| 15 | MLOps | MLflow, DVC, Docker, GitHub Actions CI/CD, data drift detection, feature stores (Feast) |
| 16 | Model Deployment | FastAPI, Cloud Run, SageMaker, Streamlit, Gradio, ONNX optimization, A/B testing |
| 17 | Big Data & Advanced Topics | PySpark, Dask, Ray, Airflow, dbt, Graph ML (GNNs), causal inference, responsible AI & SHAP |
| 18 | Portfolio & Job Readiness | GitHub portfolio, resume, analytics case studies, ML system design, coding interviews, mock interviews |

---

## Features

- **Phase navigation** — switch between the 3 learning phases with a single click
- **Week tabs** — jump to any of the 18 weeks directly
- **Expandable day cards** — each of the 126 days expands to show concepts, resources, and an exercise
- **Weekend projects** — a substantial project at the end of each week to apply the full week's material
- **Progress bar** — tracks your position across phases and weeks
- **Zero dependencies** — no npm, no Python, no build step; works in any browser

---

## How to Use

1. Open the [live site](https://r123-rb.github.io/data-science-roadmap/) or clone this repo and open `index.html` locally
2. Start at **Phase 1, Week 1, Monday**
3. Read the concepts, work through the linked resources, complete the daily exercise
4. On Sunday, build the weekend project before moving to the next week
5. Use the progress bar to track where you are across the 18 weeks

---

## Who This Is For

- **Beginners** who want a structured, day-by-day plan rather than an overwhelming list of topics
- **Self-taught practitioners** looking to identify and fill gaps in their knowledge
- **Career switchers** who need a realistic, time-boxed path from zero to job-ready
- **Educators or bootcamp organizers** who want a reference curriculum to adapt

A working knowledge of basic programming is helpful for Phase 1, but the curriculum starts from the fundamentals of Python and math, so complete beginners can follow along.

---

## Repo Structure

```
data-science-roadmap/
├── index.html          # The complete roadmap (self-contained)
├── README.md           # This file
├── LICENSE             # MIT

```

---

## Running Locally

No build step required. Clone and open:

```bash
git clone https://github.com/yourusername/data-science-roadmap.git
cd data-science-roadmap
open index.html          # macOS
# or
xdg-open index.html      # Linux
# or double-click the file in Windows Explorer
```

 
## Future Work
 
### Study Tracker Web Application
 
The roadmap currently has no way to record progress — you have to remember where you left off. A planned next step is to build a companion web application that lets you track your study activity day by day as you move through the curriculum.
 
**Planned features:**
 
- **Day completion tracking** — mark each day as done, in progress, or skipped, with progress persisted across sessions
- **Exercise log** — a text field per day to record notes, code snippets, or reflections on the exercise
- **Weekly project submission** — attach a link (e.g. GitHub repo or Colab notebook) to each weekend project for your own record
- **Progress dashboard** — a visual overview showing completion percentage per phase and per week, streaks, and total study hours logged
- **Study session timer** — a built-in timer to log how long you spent on each day's material
- **Spaced repetition reminders** — flag concepts you found difficult and surface them for review later
- **Export** — download your full study log as a CSV or PDF for portfolio documentation
 
**Likely tech stack:**
 
- Frontend: React + Tailwind CSS
- Backend: FastAPI or Supabase (for auth + database)
- Storage: PostgreSQL for user data, with a simple REST or GraphQL API
- Deployment: Vercel (frontend) + Railway or Supabase (backend)
 
Contributions toward this feature are especially welcome. If you want to take a lead on the tracker, open an issue to coordinate before starting.
 
---

## License

[MIT](LICENSE) — free to use, share, and adapt with attribution.

---

## Acknowledgements

Curriculum draws on resources from StatQuest, fast.ai, Hugging Face, scikit-learn, the Illustrated Transformer, Designing ML Systems (Chip Huyen), ISLR, Hands-On ML (Géron), Sutton & Barto, and many others — all linked directly within the roadmap.
