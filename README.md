<div align="center">

# Naga Anweesh Reddy

### AI Developer · Python & Machine Learning Trainer

Building practical AI applications with retrieval, agent workflows, and Python APIs.

[Explore my projects](https://github.com/Arjun1443?tab=repositories) · [Market Intelligence Agent](https://github.com/Arjun1443/Market-Intelligence-AI-Agent) · [LawBot](https://github.com/Arjun1443/Law-Bot)

</div>

---

## About me

I develop AI applications and teach Python, machine learning, and full-stack AI development. My work combines application building with the ability to explain technical concepts through practical examples.

My focus is **Generative AI applications, retrieval-augmented generation (RAG), and agent workflows**. I connect models and data with backend APIs and interactive interfaces, while exploring how to make AI outputs easier to inspect and use.

**Career focus:** AI Engineer and Full-Stack Generative AI Developer roles.

## Featured projects

### MoE Routing Lab — Interactive Architecture Explorer
**Purpose:** Visualize how sparse top-k routing selects experts and combines their outputs.

A Streamlit simulation with adjustable expert counts, active experts per token, token counts, and a reproducible seed. Visitors can inspect routing weights, expert utilization, and downloadable routing data.

**Engineering demonstrated:** NumPy · top-k selection · softmax normalization · weighted aggregation · interactive visualization

**Why it matters:** Makes the sparsity–utilization tradeoff tangible. The app uses synthetic logits and expert outputs; it is an educational simulation, not trained language-model inference. The accompanying study notebook retains its upstream attribution.

[**Try the app →**](https://moe-mixtureofexperts.streamlit.app/) · [View source](https://github.com/Arjun1443/MOE-Mixture_of_Experts)


### Cinema Discovery — Live Movie Catalog Explorer
**Purpose:** Browse a movie catalog and discover titles with similar wording.

A deployed Streamlit application using character-level TF–IDF and cosine similarity, with title search, release-year exploration, and ranked similarity results.

**Engineering demonstrated:** Text feature extraction · cosine similarity · catalog data parsing · cached search indexing · interactive Streamlit interfaces

**Why it matters:** Turns a data-science experiment into an accessible discovery tool. This app compares title text; it does not infer plot, genre, or personal taste. The original SVD notebook is a separate experiment requiring ratings data.

[**Try the live app →**](https://netflix-recommendation-engine-06.streamlit.app/) · [View source](https://github.com/Arjun1443/Netflix-Recommendation-Engine)


### Digit Recognition Studio — Interactive Neural Network Demo
**Purpose:** Explore handwritten-digit classification through example predictions and image uploads.

A Streamlit companion app with a compact MLP trained on scikit-learn's 8×8 digits dataset, a held-out evaluation, and per-class probability visualization. This cloud demo is distinct from the TensorFlow/MNIST experiment in the original notebook.

**Engineering demonstrated:** Neural-network classification · preprocessing pipelines · image resizing and normalization · held-out evaluation · Streamlit interfaces

**Why it matters:** Makes a computer-vision experiment accessible to visitors, with model behavior and the limitations of uploaded-image predictions made explicit.

[**Try the app →**](https://hand-written-digit.streamlit.app/) · [View source](https://github.com/Arjun1443/HWD)


### Retention Intelligence — Live Churn Classification
**Purpose:** Explore customer churn patterns and inspect predictions for individual customer scenarios.

A deployed Streamlit application using the included customer dataset, a random-forest classification pipeline, held-out evaluation, a confusion matrix, and class-probability visualization.

**Engineering demonstrated:** pandas · scikit-learn pipelines · categorical encoding · missing-value handling · classification metrics · Streamlit deployment

**Why it matters:** Demonstrates how a classification experiment can become an interactive tool for exploring retention questions. Predictions are educational estimates, not calibrated guarantees or evidence that a retention intervention will work.

[**Try the live app →**](https://customer-churn-classfication.streamlit.app/) · [View source](https://github.com/Arjun1443/Customer-Churn-Classfication)


### Insurance Cost Studio — Live ML Application
**Purpose:** Explore insurance-cost drivers and estimate charges through an interactive regression workflow.

A deployed Streamlit application with data exploration, a reproducible random-forest baseline, held-out evaluation, and scenario predictions using the repository's insurance dataset.

**Engineering demonstrated:** pandas · scikit-learn pipelines · missing-value handling · categorical encoding · model evaluation · Streamlit deployment

**Why it matters:** Turns a notebook experiment into an accessible application where visitors can inspect the data, evaluate the model, and try an input scenario. Estimates describe a learning dataset, not a real insurance quote.

[**Try the live app →**](https://health-insuranceprediction.streamlit.app/) · [View source](https://github.com/Arjun1443/HIP)


### Market Intelligence AI Agent
**Purpose:** Bring source collection, retrieval, and report generation into one research workflow.

A Python application combining a FastAPI backend, a Streamlit dashboard, Apify collection, and Qdrant retrieval. It includes local fallback behavior for exploring the pipeline without external API credentials.

**Engineering demonstrated:** API integration · semantic retrieval · pipeline orchestration · configuration · frontend/backend integration

**Why it matters:** Research workflows need more than a model response: they need collected evidence, searchable context, and a usable way to inspect results. Demo sources are synthetic and are distinguished from live research.

[View project and setup instructions →](https://github.com/Arjun1443/Market-Intelligence-AI-Agent)

### LawBot — Indian Legal Q&A
**Purpose:** Explore domain-specific question answering using Indian legal material.

A notebook-based project covering legal data preparation, instruction-format datasets, language-model fine-tuning, and retrieval-augmented generation.

**Engineering demonstrated:** Text preprocessing · JSONL dataset preparation · fine-tuning workflows · domain-specific retrieval

**Why it matters:** Specialized question answering benefits from organized domain data and retrievable context. This project explores that workflow as a learning and research prototype; it is not a substitute for professional legal advice.

[Explore the project →](https://github.com/Arjun1443/Law-Bot)

### Data Science AI Tutor
**Purpose:** Make data science concepts easier to explore through conversational explanations and practical examples.

An educational AI project focused on topic explanations, learning support, and guided exploration of data science and machine learning.

**Skills demonstrated:** AI application design · educational content design · translating technical concepts into accessible explanations

**Why it matters:** Useful learning tools connect an explanation to examples a learner can understand and apply.

[Explore the project →](https://github.com/Arjun1443/Data-Science-AI-Tutor)

### Currency Conversion Studio & Google ADK Experiment
**Purpose:** Calculate currency conversions transparently and explore agent-based task design.

A Streamlit companion app using Python Decimal arithmetic, a visitor-supplied exchange rate, fee comparison, and downloadable calculation results. The original notebook separately explores Gemini and Google ADK; the calculator does not run that agent or fetch live market rates.

**Engineering demonstrated:** Decimal arithmetic · input validation · interactive forms · CSV exports · Streamlit deployment; Google ADK and Gemini in the notebook experiment

**Why it matters:** Provides an inspectable calculation workflow with explicit assumptions, rather than relying on model-generated rates or arithmetic.

[**Try the app →**](https://ai-currency-conversion-agent-using-app-ad.streamlit.app/) · [View source and notebook](https://github.com/Arjun1443/AI-Currency-Conversion-Agent-using-Google-ADK)

## Technical toolkit

| Area | Technologies and methods |
| --- | --- |
| Programming | Python |
| Generative AI | LLM integration, RAG, semantic search, agent workflows |
| AI frameworks | LangChain, Google ADK |
| Backend & interfaces | FastAPI, Streamlit |
| Retrieval & data | Qdrant, embeddings, JSON/JSONL, text preprocessing |
| Model development | Machine learning, deep learning, fine-tuning workflows |
| Development tools | Git, GitHub, Jupyter Notebook, Python virtual environments |

## What I bring to a team

- **Application thinking:** Connecting models, retrieval, APIs, and interfaces into a coherent workflow.
- **Teaching experience:** Explaining Python and AI concepts through guided exercises and practical projects.
- **Clear communication:** Making implementation choices and project limitations understandable.
- **A learning mindset:** Building across data science, language models, and AI application development.

## Current engineering priorities

- Reproducible setup and clearer project documentation
- Meaningful tests and automated checks
- Inspectable outputs and honest evaluation of model behavior

Interested in discussing **AI engineering roles, RAG applications, agent systems, or AI education tools**? Explore the repositories above to see my work.
