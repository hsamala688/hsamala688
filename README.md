# Hi, I'm Hayden Samala 👋

I'm a student at UCLA studying Mathematics and Computer Science student, building across data engineering, machine learning, and iOS development. Right now I'm working on a production-style NFL analytics pipeline, a multi-agent system that automates health insurance appeal denials, and an iOS cognitive wellness app for geriatric patients.

---

## What I have built

**Software Engineering Intern @ Tixr** — Designed an automated feedback pipeline that routes 10K+ Intercom support tickets per day through the Claude API into a structured Supabase and Notion database. A two-stage design classifies most tickets through a deterministic keyword taxonomy and escalates only low-confidence cases to a Claude fallback, keeping token cost down at high volume.

---

## What I am working on right now

**CTO @ Bound** — Building a long-distance rideshare iOS app in SwiftUI with MVVM, using MapKit and the Google Places API for trip routing and a PostgreSQL/PostGIS model on Supabase for geospatial trip matching. Also built and deployed the marketing site from scratch using Astro.js, Typescript, and Supabase (PostgreSQL).

**[Bound WaitList Website](https://www.boundrideshare.com/)**


### 🔨 [NFL Analytics Pipeline](https://github.com/hsamala688/NFL_Projects) 🔗

What began as a one-off look at Bo Nix's 2024-2025 season grew into a full production-style data engineering and ML project. The pipeline ingests NFL play-by-play data via `nflreadpy`, stores it as Parquet, loads it into DuckDB, runs dbt transformations across three model layers, and orchestrates the whole thing with Prefect on a weekly schedule. On top sits a Streamlit dashboard and an XGBoost model that predicts pass completion probability from pre-snap features, then ranks every QB by how far they beat or trail that predicted baseline.

**Stack:** Python, DuckDB, dbt, Prefect, XGBoost, scikit-learn, Streamlit, Parquet, Plotly

---

### 🔨 [Counterclaim](https://github.com/hsamala688/war-room) 🔗

Contributing to a multi-agent AI system that automates health insurance denial appeals. The architecture runs 6 FastAPI microservices coordinated by a Python orchestrator, with the Anthropic Claude API generating appeal content across agents and shared Pydantic schemas holding the contracts together. I also ran a security audit that surfaced PHI in git history, unauthenticated inter-agent endpoints, and missing rate limiting.

**Stack:** Python, FastAPI, Anthropic Claude API, Pydantic

---

### 🔨 [NeuroQuest](https://github.com/hsamala688/NeuroQuest-N-Back-Test-Development) 🔗

Co-founding an iOS cognitive wellness app built for geriatric deployment. Written in Swift and SwiftUI with MVVM architecture, Firebase Auth for sign-in, and Cloud Firestore for longitudinal data storage. The test suite covers N-Back, Corsi Block, and a Grocery Memory module inspired by OSPAN, each with adaptive difficulty that tracks across sessions.

**Stack:** Swift, SwiftUI, Firebase, Cloud Firestore, Xcode

---

### [Fake News vs Real News (NLP)](https://github.com/hsamala688/Fake-News-Analysis) 🔗

Built with fellow UCLA student Kavin Ramesh for DataRes Fall 2025 Demo Day, and one of two teams selected to present. We trained a RoBERTa-base model and a TF-IDF logistic regression baseline to classify articles as real or fake. The interesting part was diagnosing suspiciously high accuracy and tracing it to data leakage from Reuters byline tags and subject-column artifacts, then correcting the preprocessing to recover honest benchmarks of 95% (logistic regression) and 99.64% (RoBERTa).

**Stack:** NLTK, NumPy, Pandas, HuggingFace Transformers, scikit-learn

---

### [California Wildfire Risk Prediction](https://github.com/hsamala688/CaliforniaWildfirePrediction) · [Live App](https://app-wildfire-prediction-gvp5tpcymq2uae4qndccr9.streamlit.app/) 🔗

Led a team of 6 building wildfire risk models on NASA FIRMS satellite hotspot data, Meteostat weather records, and Cal LANDFIRE vegetation layers. We unified those sources into one 800K+ row dataset, trained Logistic Regression and Random Forest models, and shipped a Streamlit dashboard with Seaborn and Matplotlib visualizations to communicate risk to technical and non-technical audiences. Joblib handles model serialization for the deployed app.

**Stack:** scikit-learn, NumPy, Pandas, Streamlit, Joblib, Seaborn, Matplotlib

---

## Let's connect

- [LinkedIn](https://linkedin.com/in/hayden-samala)
- [GitHub](https://github.com/hsamala688)
- [Email](mailto:hsamala998@gmail.com)
