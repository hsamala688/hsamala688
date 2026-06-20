# Hi, I am Hayden Samala 👋

I'm a current student at UCLA studying Mathematics and Computer Science, building across iOS development, NLP, and data engineering. I am currently working on a cognitive wellness app for geriatric patients, a pipeline that makes insurance appeal denials easier to fight, and a NFL quarterback predictive analysis project.

---

### 🔨 [Counterclaim](https://github.com/hsamala688/war-room) 🔗

Contributing to a multi-agent AI system that automates health insurance denial appeals. Built with 6 FastAPI microservices orchestrated via a Python coordinator, with the Anthropic Claude API generating appeal content across agents tied together by shared Pydantic schema contracts. Also performed a full security audit surfacing PHI exposure in git history, unauthenticated inter-agent endpoints, and rate limiting gaps.

Technologies: Python, FastAPI, Anthropic Claude API, Pydantic

---

### 🔨 [NeuroQuest N-Back Test Development](https://github.com/hsamala688/NeuroQuest-N-Back-Test-Development) 🔗

Co-founding an iOS cognitive wellness app designed for geriatric deployment. Built in Swift/SwiftUI with MVVM architecture, Firebase Auth for user authentication, and Cloud Firestore for persistent longitudinal data storage. Developing N-Back, Corsi Block, and Grocery Memory (OSPAN-inspired) test modules with adaptive difficulty tracking across sessions.

Technologies: Swift, SwiftUI, Firebase, Cloud Firestore, Xcode

---

### [California Wildfire Prediction Models](https://github.com/hsamala688/CaliforniaWildfirePrediction), [CWPM App](https://app-wildfire-prediction-gvp5tpcymq2uae4qndccr9.streamlit.app/) 🔗

Led a team of 6 building wildfire prediction models using NASA FIRMS satellite hotspot data, Meteostat weather data, and Cal LANDFIRE fuel/vegetation data. Implemented Random Forest and Linear Regression models in scikit-learn and built a Streamlit dashboard with Seaborn/Matplotlib visualizations to communicate wildfire risk to varied audiences. Joblib handles model serialization and transport to the Streamlit app.

Technologies: scikit-learn, numpy, pandas, streamlit, joblib, seaborn, matplotlib

---

### [Fake News vs Real News (NLP)](https://github.com/hsamala688/Fake-News-Analysis) 🔗

Built collaboratively with fellow first-year UCLA student Kavin Ramesh for DataRes's Fall 2025 Demo Day Challenge, and selected as one of two teams to present. Developed both a RoBERTa-base NLP model and a logistic regression model using TF-IDF vectorization to classify news articles as real or fake. The project included a full preprocessing pipeline with NLTK tokenization, stopword removal, and n-gram optimization.

Technologies: NLTK, numpy, pandas, huggingface transformers, scikit-learn

---

### [NFL Analytics Pipeline](https://github.com/hsamala688/NFL_Projects) 🔗

What started as a one-off analysis of Bo Nix's 2024-2025 season has grown into a full production-style data engineering and machine learning project. The pipeline ingests NFL play-by-play data via `nflfastpy`, stores it as Parquet, loads it into DuckDB, runs dbt transformations across three model layers, and orchestrates everything with Prefect on a weekly schedule. On top of that sits a Streamlit dashboard and an XGBoost model that predicts pass completion probability from pre-snap situational features, used to rank every QB by how much they outperform or underperform their predicted baseline.

Technologies: Python, DuckDB, dbt, Prefect, Streamlit, XGBoost, scikit-learn, Parquet, Plotly

---

## Let's Connect

- [LinkedIn](https://linkedin.com/in/hayden-samala)
- [GitHub](https://github.com/hsamala688)
- [Email](mailto:hsamala998@gmail.com)
