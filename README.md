# Roberto Casaluce

**Email:** rcasaluce@yahoo.co.uk  
**GitHub:** https://github.com/rcasaluce  

Computer scientist with a PhD in Artificial Intelligence and a background in political science and data science, applied to computational social science and policy-relevant research. My work focuses on the evaluation and validation of AI and simulation-based systems, including agentic workflows, machine learning and NLP. I develop reproducible methods, benchmarks and data pipelines for research involving textual, behavioural and geospatial data. My experience combines methodological research, applied AI and science-for-policy work at the Joint Research Centre.

---

## Core Technical Profile

- **Applied AI / LLM evaluation:** Prompt and tool-use strategy design, benchmark construction, robustness testing, evaluation pipelines, scoring and aggregation, and comparative reporting across multiple LLM backends, including LangChain- and OpenAI API-based workflows.

- **NLP / ML:** Transformer-based modelling for tasks such as named entity recognition, sentence classification, and rhetorical classification; experiment design, reproducible workflows, model evaluation, error analysis, annotation guideline development, data labelling, and dataset curation and validation.

- **Data and software engineering for research:** Python-based data-processing pipelines, dataset preparation and provenance tracking, reusable web-scraping and online data-acquisition tools—including USPTO patent scraping and YouTube crawling—and PostgreSQL-backed applications developed with Flask and Django.

- **Validation and process analysis:** Statistical Model Checking, Process Mining, conformance diagnostics, traceable evaluation protocols, benchmark design, and white-box validation approaches.

- **Modelling and simulation:** Agent-based modelling and discrete-event simulation using RisQFLan, QFLan, SCEL, SimPy, and Mesa.

- **Geospatial and Earth Observation workflows:** openEO, Copernicus Earth Observation services, and Sentinel Hub Evalscript for satellite-data processing and analysis.

- **Reproducibility and deployment:** Containerised and version-controlled research workflows using Docker, Git/GitHub, Linux, and MLflow, with experience deploying web-based applications through Heroku.

- **Selected tech stack:** Python, R, SQL/PostgreSQL, PyTorch, Hugging Face Transformers, scikit-learn, pandas, NumPy, matplotlib, Flask, Django, Docker, Git/GitHub, Linux, MLflow, SimPy, Mesa, openEO, LangChain, and OpenAI API-based pipelines.

---

## Research and applied work experience

### Scientific Trainee — Directorate T, Data Governance and Services (JRC.T.4) | Joint Research Centre (JRC), Ispra, Italy
**Dates:** 01/11/2025 - 31/03/2026  
**Sectors:** Research  
**Main activities and responsibilities:**  
- Contributed to an LLM-enabled geospatial agent integrating heterogeneous geospatial data sources into tool-augmented workflows for geospatial reasoning (retrieval + function calling).
- Built an end-to-end evaluation pipeline in GPT@JRC across supported LLM backends (dataset ingestion -> prompt/template variants -> tool-call execution -> scoring/aggregation -> reporting).
- Designed and compared prompting and tool-use strategies, including controlled prompt perturbations; implemented multiple evaluation schemes (LLM-as-a-judge, string-based MCQ accuracy, and log-probability scoring for constrained answers) to assess reliability and sensitivity to prompt changes. Repo: https://github.com/rcasaluce/when2call-api-eval-suite
- Created human-in-the-loop benchmark variants (data perturbation + quality checks) to stress-test model behaviour and tool-call robustness under distribution shifts. Repo: https://github.com/rcasaluce/when2call-hil-perturbation-pipeline
- Prepared and integrated geospatial datasets (including openEO process graphs and, where applicable, vector/raster metadata), ensuring consistency, provenance, and usability within the agent pipeline; applied expert-in-the-loop validation during database curation.
- Converted Sentinel Hub Evalscript workflows into openEO notebooks to extract reusable process graphs.

### Computer Scientist (Social Statistics Project) — Research Fellow | University of Catania
**Dates:** 03/09/2024 - 25/10/2025  
**Sectors:** Education / Research  
**Main activities and responsibilities:**  
- Designed and implemented a web-based data-collection platform (Python/Flask), deployed on Heroku with a PostgreSQL backend, to collect ego-centred collaboration networks via a customizable questionnaire.
- Contributed to survey design and sampling strategy for collecting ego-network data on scientific collaboration.  
**Web app:** https://masconet-7287ceecf789.herokuapp.com/available_surveys  
**Code:** https://github.com/rcasaluce/MaScoNet  

### Research Scientist (Simulation Validation & Process Mining) — Doctoral Researcher | University of Pisa & Sant'Anna School of Advanced Studies, Pisa
**Dates:** 01/11/2021 - 03/09/2024  
**Sectors:** Doctoral Research  
**Main activities and responsibilities:**  
- Developed a white-box validation framework for simulation-based models by combining Statistical Model Checking and Process Mining.
- Designed traceable and reproducible evaluation protocols (documented assumptions, measurable properties, audit-ready experiments).
- Produced visual conformance diagnostics to identify discrepancies between intended and simulated processes; analysed error modes and robustness.
- Co-authored peer-reviewed publications and maintained reproducible research artefacts (code, scripts, and documentation).

### Data Scientist (NLP) — Predictive Jurisprudence (EU project) | Predictive Justice platform  
Research Fellow (7-month postgraduate research grant) — Sant'Anna School of Advanced Studies, Pisa  
**Dates:** 01/04/2021 - 30/10/2021  
**Sectors:** Education / Research  
**Main activities and responsibilities:**  
- Prepared and curated legal-text datasets for modelling, including preprocessing and entity annotation strategy for anonymization tasks.
- Trained and evaluated Transformer-based NER models to identify PII/entities for anonymization in court decisions (HuggingFace, spaCy, PyTorch/TF).
- Developed sentence-type / rhetorical function classification using Transformer models; incorporated rule-based rhetorical schemes to improve interpretability and consistency of predictions.
- Ran systematic experiments and tracked results with MLflow; ensured reproducibility with Docker and Git on a Linux environment.
- Contributed to dissemination by writing articles for the project blog.  
**Project website:** https://www.predictivejurisprudence.eu/  

### Data Scientist (NLP / Innovation Policy) — Research Assistant | ETH Zurich, Zurich, Switzerland
**Dates:** 01/10/2020 - 31/03/2021  
**Sectors:** Education / Research  
**Main activities and responsibilities:**  
- Extended MSc thesis work by adding new patent batches (clean energy technologies storage) and running additional experiments to test model generalization.
- Used automated patent classification outputs to operationalize a large-scale quantitative measure of technological complexity (method development + empirical implementation).
- Contributed to a policy-facing analysis to support decision-makers on public policy design for clean-energy innovation.

### Visiting MSc Thesis Project (NLP / ML) — Master's Thesis Project | ETH Zurich, Zurich, Switzerland
**Dates:** 01/02/2020 - 30/09/2020  
**Sectors:** Education / Research  
**Project:** Automated Patent Classification by Type of Innovation for Clean Energy Storage Technologies  
**Main activities and responsibilities:**  
- Conducted literature review and built a large-scale patent NLP dataset via web scraping and preprocessing (USPTO + EPO).
- Trained domain-specific word embeddings on ~3.5M patents to improve representation of technical language.
- Implemented and evaluated binary and multi-class text classification models (claims + abstracts) to predict innovation type (e.g., product vs process), running the full experimental pipeline end-to-end.
- Ensured reproducibility via scripted workflows; documented results in a final report and released code.
- Built an end-to-end web app (Django) to fetch patent documents and classify claims in real time (prototype; currently offline).  
**Repo (code/report):** https://github.com/rcasaluce/final_project/  
**Repo (web app):** https://github.com/rcasaluce/Django_app-patents_classification  

---

## Selected research outputs and professional activities


<summary><strong>Publications</strong></summary>

- Casaluce, R., Tschaikowski, M., Vandin, A. *White-box validation of collective adaptive systems by statistical model checking and process mining.* In **Leveraging Applications of Formal Methods, Verification and Validation**. REoCAS Colloquium in Honor of Rocco De Nicola, pages 204–222, Cham, 2025. Springer Nature Switzerland. ISBN 978-3-031-73709-1.
- Casaluce, R., Burattin, A., Chiaromonte, F., Lafuente, A. L., Vandin, A. *Enhancing threat model validation: A white-box approach based on statistical model checking and process mining.* In **DAMOCLES 2024** (AVI ’24 workshop), Arenzano, Italy, June 4, 2024, CEUR Workshop Proceedings, vol. 3713, pp. 9–20. PDF: https://ceur-ws.org/Vol-3713/paper_2.pdf
- Casaluce, R., Burattin, A., Chiaromonte, F., Lafuente, A. L., Vandin, A. *White-box validation of quantitative product lines by statistical model checking and process mining.* **Journal of Systems and Software** 210 (2024) 111983.
- Casaluce, R., Burattin, A., Chiaromonte, F., Vandin, A. (2023, February). *Process Mining Meets Statistical Model Checking: Towards a Novel Approach to Model Validation and Enhancement.* In **Business Process Management Workshops: BPM 2022 International Workshops**, Revised Selected Papers (pp. 243–256). Springer.
- Casaluce, R. *Process mining meets statistical model checking to explain threat models: Novel approach to model validation and enhancement (extended abstract).* In **ICPM Doctoral Consortium and Demo Track 2022**, Bolzano, Italy, October 2022. CEUR Workshop Proceedings, vol. 3299, pp. 13–17.




<summary><strong>Working paper</strong></summary>

- Schmidt, T., Malhotra, A., Kaack, L., and Casaluce, R. (2023, November). *Technological Complexity, Experience Rates and Low-Carbon Innovation and Industrial Policies: A Novel Approach Leveraging Machine Learning and Patent Networks.* Presented at **APPAM Fall Research Conference 2023**.  
  https://appam.confex.com/appam/2023/meetingapp.cgi/Paper/50196




<summary><strong>Presentations and talks</strong></summary>

- **ESRA 2025**, Utrecht, Netherlands, 14–18 July 2025. Presentation: *“MaScoNet: A Web-Based Application for Mapping Formal and Informal Scientific Collaborations”*.
- **Data Science & Social Research (DSSR)**, 5th International Conference, Pescara, Italy, 19–21 February 2025.
- **DAMOCLES 2024** (AVI ’24 workshop), Arenzano (GE), Italy, 4 June 2024.
- **ICPM 2022**, Doctoral Consortium, Bolzano, Italy, 23–28 October 2022.
- **DEC2H 2022** (BPM 2022), Muenster, Germany, 11–16 September 2022.


<summary><strong>Peer-review activities</strong></summary>

- Reviewer: Commit2Data: Big Data Handling, Analytics & Applications 2023 — https://commit2data.nl/en/
- Sub-reviewer: The 5th 2023 International Conference on Computer Systems and Communication Technology — http://www.iccsct.org/
- Sub-reviewer: 18th International Working Conference on Variability Modelling of Software-Intensive Systems 2024 — https://vamosconf.net/2024
- PC member: Artifact Evaluation for QEST + FORMATS 2024 — https://www.qest-formats.org/artifacts.html


<summary><strong>Visiting position abroad</strong></summary>

- Two-week visiting appointment at the Technical University of Denmark (DTU), December 2022, invited by Prof. Alberto Lluch Lafuente.
- Research carried out during this stay led to the article: *“White-Box Validation of Quantitative Product Lines by Statistical Model Checking and Process Mining”.*



---

## Education and advanced training

### PhD in Artificial Intelligence (Computer Science) — University of Pisa & Sant'Anna School of Advanced Studies, Pisa
**Dates:** 01/11/2021 - 16/05/2025  
**Level:** EQF 8  
**Grade:** Excellent (Ottimo)  
- Selected doctoral coursework: Explainable AI; Social Network Analysis; Statistical Learning and Large Data; Applied Statistics; Programming & Data Analytics.
- Doctoral thesis: *White-Box Validation of Simulated Models using Statistical Model Checking and Process Mining.*
- Built a validation methodology combining Statistical Model Checking and Process Mining to assess simulation models against intended process specifications.
- Developed traceable, reproducible evaluation protocols and visual conformance diagnostics to identify deviations and error modes.

### MSc in Data Science (Computer Science) — Birkbeck, University of London
**Dates:** 2018 - 2020  
**Level:** EQF 7  
- Selected coursework: Principles of Programming (Python); Big Data Analytics (R); Programming with Data (SQL/Python); Applied Machine Learning; NLP & Information Retrieval; Data Science Techniques & Applications; Computer Systems / Fundamentals of Computing.
- Key focus: ML/NLP modelling and evaluation; data wrangling at scale (SQL/Python); reproducible workflows.
- Dissertation: *Automated Patent Classification by Type of Innovation for Clean Energy Storage Technologies* (hosted at ETH Zurich; USPTO/EPO corpus ~3.5M patents).

### MSc in Government, Policy and Politics — Birkbeck, University of London
**Dates:** 2014 - 2017  
**Level:** EQF 7  
- Qualitative Social Research: qualitative research design; interviews and document analysis; qualitative content analysis (codebook development and coding); research ethics.
- Intermediate Quantitative Social Research: research design; measurement and operationalization; regression-based analysis; evaluation and interpretation of results.
- Public Policy: governance and institutional analysis; policy processes and implementation (incl. implications for platform regulation and content moderation).
- Modern British Politics: political institutions and contemporary political communication; media ecosystems (relevant to misinformation/propaganda studies).
- MA dissertation: *Voter Behaviour in the UK General Election 2015.*
- Used BES panel data (multiple waves) to examine links between EU/migration rhetoric and vote intention/choice over time.
- Methods: panel/longitudinal regression in R (CRAN) and Stata; model estimation, robustness checks, and interpretation.

### BA in Political Science — University of Trieste
**Dates:** 2013  
**Level:** EQF 6  
- BA dissertation: *Statistical Methods for Estimating Vote Flows* (orig. *Alcune metodologie statistiche per la stima dei flussi elettorali*).
- Critical comparison of Ecological Inference (EI) (Gary King) and survey-based approaches to estimating electoral vote flows.
- Discussed key assumptions and sources of bias, with emphasis on ecological fallacy, aggregation bias, uncertainty/identifiability, and robustness of estimates.

<details>
<summary><strong>Specialization schools</strong></summary>

- PhD School on Artificial Intelligence and Cybersecurity, December 2023 (online), Sapienza University of Rome, Rome, Italy.
- PhD AI & Society 2022 Summer School, Pisa, Italy, 4–8 July 2022.
- Lipari School on Computational Complex and Social Systems — *“Generative AI, Human Decision and Machine Prediction: Models, Algorithms, Platforms and Ethics”*, Lipari Island, Italy, 14–20 July 2024.

</details>

---

## Additional skills and information

### Technical skills
- Very good programming skills in **Python** (data processing, NLP/ML pipelines, automation scripts).
- Good programming skills in **R** (statistical analysis on survey/panel data).
- Good command of **SQL** (PostgreSQL; familiarity with Hive and Impala).
- Very good knowledge of **Machine Learning and NLP**, including transformer-based modelling and experiment management.
- Good command of **PyTorch** and good working knowledge of **HuggingFace** tooling.
- Good knowledge of **LLM-based workflows and tool use** (LangChain and OpenAI API-based pipelines: retrieval/tool calling, prompt design, evaluation and robustness testing).
- Good knowledge of **pandas / numpy / matplotlib / scikit-learn**.
- Good command of **Docker** for containerized experimentation and deployment.
- Very good experience with **Git/GitHub** (version control, issue tracking, reproducible codebases).
- Good command of **Flask** and **Django** for web applications.
- Good knowledge of **Linux** (shell commands, environment management).
- Very good command of **MS Office** (Word, Excel, PowerPoint).

### Languages
- Italian: Mother tongue.
- English: CEFR entries reported: Listening/Comprehension C2; Reading C1; Oral Interaction C1.

### Interpersonal and communication skills
- Excellent communication skills in Italian and English (stakeholder-oriented reporting; international research experience).
- Excellent ability to work both collaboratively and independently in interdisciplinary and international teams.
- Strong scientific writing and dissemination skills; experience producing guidelines for data annotation and evaluation protocols.
- Teaching and mentoring skills (three years of hands-on Machine Learning teaching in Python-based labs).

### Organisational skills
- Excellent organisational skills developed from coordinating studies and work commitments abroad in London (2014–2020).
- Excellent deadline management skills developed by working simultaneously in two roles at Goldsmiths Library in 2019 while attending the MSc in Data Science.

<details>
<summary><strong>Certifications</strong></summary>

- DeepLearning.AI TensorFlow Developer — DeepLearning.AI on Coursera (10/01/2021).  
  Included courses: (1) Introduction to TensorFlow for AI/ML/DL; (2) CNNs in TensorFlow; (3) NLP in TensorFlow; (4) Sequences, Time Series and Prediction.
- Learning Django — LinkedIn (15/12/2020).
- Advanced NLP with Python for Machine Learning — LinkedIn (15/11/2020).
- Foundations for Big Data Analysis with SQL — Cloudera Coursera (25/10/2020).
- Specialized Module on Human Health and Climate Change — UN CC:Learn (06/01/2018).
- National Adaptation Plans: Building Climate Resilience in Agriculture — UN CC:Learn (01/11/2017).

</details>
