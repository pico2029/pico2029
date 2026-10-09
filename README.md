Matteo Picozzi

**Computer Science MSc student at the University of Milano-Bicocca**  
Python · Machine Learning · Backend Development · Internet of Things

I enjoy building applications that connect data, machine learning, and software systems. Through academic projects and a bachelor's thesis internship, I have worked on image classification, personalized recommendations, backend APIs, and distributed IoT monitoring.

My main programming language is Python. I am interested in understanding the whole application workflow: collecting and preparing data, evaluating models, implementing backend services, and making results accessible through interfaces.

[LinkedIn](https://www.linkedin.com/in/matteo-picozzi29) · [Email](mailto:matteo2902@icloud.com)

## About me

- Based in Brugherio, in the Milan metropolitan area, Italy.
- Pursuing a Master's degree in Computer Science at the University of Milano-Bicocca.
- Bachelor's degree in Computer Science from the same university.
- Interested in opportunities involving software development, applied machine learning, and IoT.
- Italian native speaker; English at B2 level.

## Technical skills

The technologies below reflect tools I have used in academic projects or during my thesis internship.

| Area | Technologies and methods |
| --- | --- |
| Programming | Python, JavaScript, C++, C# |
| Machine learning and deep learning | scikit-learn, TensorFlow, Keras; decision trees, neural networks, CNNs, transfer learning, fine-tuning |
| Data preparation and analysis | Pandas, NumPy, SciPy, Matplotlib, Seaborn; exploratory analysis, preprocessing, feature engineering |
| Model evaluation | Classification metrics, precision–recall analysis, ROC-AUC, Brier score, validation-based threshold selection |
| Backend and APIs | Flask, REST APIs, JSON; data persistence and frontend–backend integration |
| Recommendation and semantic search | Sentence Transformers, ChromaDB, SPARQL; semantic embeddings, DBpedia/Wikidata enrichment |
| IoT and embedded systems | ESP8266, Arduino/C++, MQTT, InfluxDB, sensor integration, Web of Things Thing Descriptions |
| Interfaces and application tools | Streamlit, Plotly, HTML, CSS, Docker Compose, Jupyter |
| Game development | Unity, C#, Rigidbody, WheelCollider, Shader Graph, Unity UI, TextMesh Pro |

## Selected projects

### K-RSS — Knowledge-Aware YouTube Recommendation System

Co-developed a personalized recommendation application for YouTube videos collected through RSS feeds.

- Combined video text with information from DBpedia and Wikidata to generate knowledge-enriched embeddings using Sentence Transformers.
- Built a collection and embedding pipeline with vector storage and retrieval in ChromaDB.
- Used semantic similarity with optional re-ranking based on shared metadata entities and categories.
- Captured initial preferences through onboarding, updated the user profile from likes, and excluded disliked videos from future recommendations.
- Provided exploration controls, channel-diversity filtering, and a Streamlit interface with interactive visualizations.
- Containerized application components with Docker Compose.

**Stack:** Python, Sentence Transformers, ChromaDB, SPARQL, Streamlit, Plotly, Docker Compose.

### [EPMS — IoT Monitoring and Remote Management](https://github.com/pico2029/Epms-monitoring-system)

Developed a distributed monitoring prototype connecting three ESP8266 sensor nodes to a central Python application.

- Collected temperature, humidity, light, and door-status measurements, and monitored water level through ultrasonic distance sensing.
- Used MQTT for discovery, telemetry, and events, with HTTP APIs for remote configuration.
- Published Web of Things Thing Descriptions describing device capabilities.
- Built a Flask dashboard for centralized monitoring and configuration, with telemetry storage through InfluxDB.
- Integrated Telegram alerts and external weather and sunrise–sunset services.

**Stack:** Python, Flask, ESP8266, Arduino/C++, MQTT, InfluxDB, HTML, CSS, JavaScript.

### Multi-Label Image Classification with CNNs and EfficientNetB0

Group project for the Advanced Machine Learning course, exploring image classification across the 20 PASCAL VOC 2012 object categories.

- Compared a custom CNN trained from scratch with ImageNet-pretrained EfficientNetB0, using a frozen backbone followed by fine-tuning.
- Applied image preprocessing, training-time augmentation, and weighted binary cross-entropy to address class imbalance.
- Evaluated predictions using mAP, micro/macro F1, and precision–recall analysis.
- Selected per-class classification thresholds on validation data and applied them to an internal test split.

**Stack:** Python, TensorFlow/Keras, scikit-learn, NumPy, Pandas, Matplotlib, Seaborn.

The repository distinguishes historical course-project results from later code revisions. Those saved results are not verified scores for the revised implementation or official VOC benchmark results.

### [Cardiovascular Disease Classification](https://github.com/pico2029/Cardiovascular-disease-classification)

Developed an educational classification project using clinical, anthropometric, and lifestyle features from a public cardiovascular dataset.

- Assessed data quality and engineered features such as age in years and BMI.
- Built preprocessing pipelines for implausible measurements, missing values, categorical encoding, and numerical scaling.
- Compared a decision tree with a feedforward neural network, using hyperparameter selection, dropout, and L2 regularization.
- Evaluated classification performance and probabilistic predictions, including ROC-AUC and Brier score.
- Explored how validation-selected thresholds change recall, false negatives, and false positives.

**Stack:** Python, scikit-learn, TensorFlow/Keras, Pandas, NumPy, SciPy, Matplotlib, Seaborn, Jupyter.

### Racers — Arcade Racing Game in Unity

Developed a single-player racing game set in a low-poly urban environment, with vehicle selection and daytime/nighttime settings.

- Implemented driving mechanics using Rigidbody and WheelCollider physics.
- Built waypoint-based opponent behavior with recovery actions and adaptive speed adjustment.
- Managed countdowns, checkpoint validation, laps, timers, and a persistent local leaderboard stored in JSON.
- Added tutorials, menus, animated end-of-race sequences, engine audio, and visual feedback such as smoke, skid marks, speed lines, and camera shake.

**Stack:** Unity, C#, Shader Graph, Unity UI, TextMesh Pro, JSON.

## Bachelor's thesis internship

### Epimetheus — Backend Development for a Clinical Decision Support System

**University of Milano-Bicocca · March–June 2024**

During my bachelor's thesis internship, I contributed to Epimetheus, a clinical decision support application designed to estimate recovery outcomes following orthopedic procedures.

- Extended the Python/Flask backend with REST API endpoints for collecting and storing user evaluation questionnaire responses.
- Configured communication between the backend and React frontend for local execution.
- Documented application setup and startup procedures.

My contribution focused on backend development and application integration. The predictive models were part of the existing application.

**Thesis:** *Development and Implementation of a Decision Support System in the Medical Field.*

## What I would like to work on

- Software applications that turn data and model outputs into useful functionality.
- Python backend services and API integrations.
- Recommendation systems and semantic search.
- Connected devices, telemetry, and monitoring applications.

I am interested in contributing to a team where I can apply my project experience, strengthen my software engineering skills, and learn from experienced developers.

## Contact

- **LinkedIn:** [matteo-picozzi29](https://www.linkedin.com/in/matteo-picozzi29)
- **Email:** [matteo2902@icloud.com](mailto:matteo2902@icloud.com)
- **GitHub:** [pico2029](https://github.com/pico2029)
