# Curriculum Vitae

**Email:** [rcasaluce@yahoo.co.uk](mailto:rcasaluce@yahoo.co.uk)  
**GitHub:** [github.com/rcasaluce](https://github.com/rcasaluce)

Computer scientist with a PhD in Artificial Intelligence and a background in political science and data science, applied to computational social science and policy-relevant research. My work focuses on the evaluation and validation of AI and simulation-based systems, including agentic workflows, machine learning, and NLP. I develop reproducible methods, benchmarks, and data pipelines for research involving textual, behavioural, and geospatial data. My experience combines methodological research, applied AI, and science-for-policy work at the Joint Research Centre.

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

## Research and Professional Experience

### Scientific Trainee — Joint Research Centre (JRC), European Commission, Ispra, Italy
**Directorate T, Data Governance and Services (JRC.T.4)**  
**Dates:** 01/11/2025–31/03/2026  
**Sector:** Research

- Designed and evaluated prompting and tool-use strategies for LLMs, including retrieval and function calling, using consolidated benchmarks and human-in-the-loop variants.
- Developed a prototype LLM-based GeoAI agent using Copernicus openEO to translate natural-language Earth Observation requests into openEO workflows and process graphs.
- Built an end-to-end evaluation pipeline in GPT@JRC across supported LLM backends: dataset ingestion, prompt and template variants, tool-call execution, scoring and aggregation, and comparative reporting.
- Implemented and compared multiple evaluation schemes, including LLM-as-a-judge, string-based multiple-choice accuracy, and log-probability scoring for constrained answers, to assess reliability and sensitivity to prompt changes.
- Created human-in-the-loop benchmark variants using data perturbation and quality checks to stress-test model behaviour and tool-call robustness under distribution shifts.
- Curated a geospatial dataset comprising openEO process graphs, expert-reviewed descriptions, outputs, and metadata, with expert-in-the-loop validation. The dataset forms the basis of a Data Descriptor manuscript being prepared for submission to *Scientific Data*.
- Converted around 40 Sentinel Hub Evalscript workflows, mainly Sentinel-2, into reusable openEO notebooks and process graphs to support portability, reuse, and evaluation.
- **Evaluation suite:** [when2call-api-eval-suite](https://github.com/rcasaluce/when2call-api-eval-suite)
- **Human-in-the-loop perturbation pipeline:** [when2call-hil-perturbation-pipeline](https://github.com/rcasaluce/when2call-hil-perturbation-pipeline)

### Research Fellow — University of Catania, Catania, Italy
**Social Statistics Project**  
**Dates:** 03/09/2024–25/10/2025  
**Sectors:** Education / Research

- Supported a social statistics research project on methodological approaches for analysing scientific collaboration networks using ego-network data.
- Contributed to the design of the survey instrument and sampling strategy for scientific collaboration data collection.
- Designed and deployed a custom web platform for ego-network data collection through configurable questionnaires, using Python/Flask, PostgreSQL, and Heroku.
- **Web application:** [Ego Network Data — available surveys](https://www.egonetworkdata.it/available_surveys)
- **Source code:** [MaScoNet on GitHub](https://github.com/rcasaluce/MaScoNet)

### PhD Researcher in Computer Science / Artificial Intelligence — University of Pisa and Scuola Superiore Sant'Anna, Pisa, Italy
**Dates:** 01/11/2021–16/05/2025  
**Sector:** Doctoral Research

- Developed a white-box validation methodology for simulation models by combining Statistical Model Checking and Process Mining.
- Defined traceable and reproducible evaluation protocols, including documented assumptions, measurable properties, conformance diagnostics, and error analysis.
- Produced visual conformance diagnostics to identify discrepancies between intended and simulated processes and analysed error modes and robustness.
- Produced peer-reviewed publications and maintained reproducible research artefacts, including code, scripts, and documentation.

### Postgraduate Research Fellow / Data Scientist (NLP) — Predictive Jurisprudence Project, Scuola Superiore Sant'Anna, Pisa, Italy
**Dates:** 01/04/2021–30/10/2021  
**Sectors:** Education / Research

- Prepared and curated legal-text datasets for anonymisation and text classification, with particular attention to GDPR requirements, personal-data protection, and privacy-by-design principles.
- Developed annotation guidelines and contributed to data labelling with a team of annotators.
- Trained and evaluated Transformer-based models for named entity recognition and rhetorical or sentence-level classification of judicial decisions using Hugging Face, spaCy, and PyTorch/TensorFlow.
- Incorporated rule-based rhetorical schemes to improve the interpretability and consistency of predictions.
- Conducted reproducible experimentation with MLflow, Docker, and Git in a Linux environment.
- Contributed to project dissemination through articles for the project blog.
- **Project website:** [Predictive Jurisprudence](https://www.predictivejurisprudence.eu/)

### Research Assistant — ETH Zurich, Zurich, Switzerland
**NLP / Innovation Policy**  
**Dates:** 01/10/2020–31/03/2021  
**Sectors:** Education / Research

- Extended MSc thesis work with new patent batches in clean-energy storage technologies and additional experiments to test model generalisation.
- Used automated patent classification outputs to operationalise a large-scale quantitative measure of technological complexity.
- Contributed to policy-facing analysis intended to support decision-makers in the design of public policies for clean-energy innovation.

### Visiting MSc Thesis Researcher — ETH Zurich, Zurich, Switzerland
**Project:** Automated Patent Classification by Type of Innovation for Clean Energy Storage Technologies  
**Dates:** 01/02/2020–30/09/2020  
**Sectors:** Education / Research

- Conducted a literature review and designed large-scale patent data-extraction pipelines using USPTO and EPO sources.
- Built and processed an NLP dataset of approximately 3.5 million patent documents and trained domain-specific word embeddings to improve the representation of technical language.
- Implemented and evaluated binary and multi-class text-classification models using patent claims and abstracts to predict innovation types, such as product versus process innovation.
- Ran the complete experimental pipeline end to end and ensured reproducibility through scripted workflows and documentation.
- Developed a Django web prototype for retrieving patent documents and classifying claims in real time; the prototype is currently offline.
- **Code and report:** [final_project](https://github.com/rcasaluce/final_project/)
- **Django prototype:** [Django_app-patents_classification](https://github.com/rcasaluce/Django_app-patents_classification)

---

## Education

### PhD in Artificial Intelligence — University of Pisa and Scuola Superiore Sant'Anna, Pisa, Italy
**Dates:** 01/11/2021–16/05/2025  
**Level:** EQF 8  
**Final grade:** Excellent (*Ottimo*)

- **Thesis:** *White-Box Validation of Simulated Models using Statistical Model Checking and Process Mining.*
- Selected coursework: Explainable AI; Social Network Analysis; Statistical Learning and Large Data; Applied Statistics; Programming & Data Analytics.
- Developed a validation methodology combining Statistical Model Checking and Process Mining to assess simulation models against intended process specifications.
- Developed traceable and reproducible evaluation protocols and visual conformance diagnostics to identify deviations and error modes.

### Master of Science in Data Science — Birkbeck, University of London, London, United Kingdom
**Dates:** 2018–2020  
**Level:** EQF 7

- Selected coursework: Principles of Programming (Python); Big Data Analytics (R); Programming with Data (SQL/Python); Applied Machine Learning; NLP & Information Retrieval; Data Science Techniques & Applications; Computer Systems / Fundamentals of Computing.
- Main focus: ML/NLP modelling and evaluation, large-scale data wrangling with SQL and Python, and reproducible workflows.
- **Dissertation:** *Automated Patent Classification by Type of Innovation for Clean Energy Storage Technologies*, hosted at ETH Zurich and based on a USPTO/EPO corpus of approximately 3.5 million patents.

### Master of Science in Government, Policy and Politics — Birkbeck, University of London, London, United Kingdom
**Dates:** 2014–2017  
**Level:** EQF 7

- Qualitative Social Research: research design, interviews and document analysis, qualitative content analysis, codebook development and coding, and research ethics.
- Intermediate Quantitative Social Research: research design, measurement and operationalisation, regression-based analysis, and evaluation and interpretation of results.
- Public Policy: governance and institutional analysis, policy processes, and implementation, including implications for platform regulation and content moderation.
- Modern British Politics: political institutions, contemporary political communication, and media ecosystems relevant to misinformation and propaganda studies.
- **Dissertation:** *Voter Behaviour in the UK General Election 2015.*
- Used British Election Study panel data across multiple waves to analyse relationships between EU and migration rhetoric and vote intention or choice over time.
- Methods: panel and longitudinal regression in R and Stata, model estimation, robustness checks, and interpretation.

### Bachelor's Degree in Political Science — University of Trieste, Trieste, Italy
**Year:** 2013  
**Level:** EQF 6

- **Dissertation:** *Alcune metodologie statistiche per la stima dei flussi elettorali* (*Statistical Methods for Estimating Vote Flows*).
- Critically compared Gary King's Ecological Inference approach with survey-based methods for estimating electoral vote flows.
- Discussed assumptions and sources of bias, including ecological fallacy, aggregation bias, uncertainty, identifiability, and robustness.

---

## Teaching Experience

- **Teaching module: “Machine Learning for Social Science” (24 hours)** — University of Trieste, Department of Political and Social Sciences, June 2025.
- **MSc seminars (6 hours)** — University of Catania, Department of Political and Social Sciences, November 2024: “Introduction to Social Network Analysis with R” and “Introduction to Text Analysis with R”.
- **Teaching module: “Machine Learning for Social Science” (24 hours)** — University of Trieste, Department of Political and Social Sciences, May–June 2024.
- **Teaching module: “Machine Learning for Social Science” (15 hours)** — University of Trieste, Department of Political and Social Sciences, May–June 2023.

## Student Supervision

- **Co-supervision of final dissertation** — University of Trieste, Department of Political and Social Sciences, November 2024–February 2025.
- Co-supervised, with Prof. De Stefano, Lorenzo Morsut's dissertation: *Elon Musk on YouTube: A Quantitative Content Analysis of a Selection of Videos*.
- Final mark: 110/110 cum laude.

---

## Selected Research Outputs and Professional Activities

### Publications

- Casaluce, R., Tschaikowski, M., Vandin, A. *White-box validation of collective adaptive systems by statistical model checking and process mining.* In **Leveraging Applications of Formal Methods, Verification and Validation**. REoCAS Colloquium in Honor of Rocco De Nicola, pp. 204–222. Springer Nature Switzerland, 2025. ISBN 978-3-031-73709-1.
- Casaluce, R., Burattin, A., Chiaromonte, F., Lafuente, A. L., Vandin, A. *Enhancing threat model validation: A white-box approach based on statistical model checking and process mining.* In **Proceedings of the First International Workshop on Detection And Mitigation Of Cyber attacks that exploit human vuLnerabilitiES (DAMOCLES 2024)**, CEUR Workshop Proceedings, vol. 3713, pp. 9–20, 2024. [PDF](https://ceur-ws.org/Vol-3713/paper_2.pdf)
- Casaluce, R., Burattin, A., Chiaromonte, F., Lafuente, A. L., Vandin, A. *White-box validation of quantitative product lines by statistical model checking and process mining.* **Journal of Systems and Software**, 210, 111983, 2024.
- Casaluce, R., Burattin, A., Chiaromonte, F., Vandin, A. *Process Mining Meets Statistical Model Checking: Towards a Novel Approach to Model Validation and Enhancement.* In **Business Process Management Workshops: BPM 2022 International Workshops**, Revised Selected Papers, pp. 243–256. Springer, 2023.
- Casaluce, R. *Process mining meets statistical model checking to explain threat models: Novel approach to model validation and enhancement (extended abstract).* In **Proceedings of the ICPM Doctoral Consortium and Demo Track 2022**, CEUR Workshop Proceedings, vol. 3299, pp. 13–17, 2022.

### Working Paper

- Schmidt, T., Malhotra, A., Kaack, L., and Casaluce, R. *Technological Complexity, Experience Rates and Low-Carbon Innovation and Industrial Policies: A Novel Approach Leveraging Machine Learning and Patent Networks.* Working paper presented at the **APPAM Fall Research Conference**, 2023. [Conference page](https://appam.confex.com/appam/2023/meetingapp.cgi/Paper/50196)

### Conference Presentations and Talks

- **11th Conference of the European Survey Research Association (ESRA)**, Utrecht, Netherlands, 14–18 July 2025. Presentation: *MaScoNet: A Web-Based Application for Mapping Formal and Informal Scientific Collaborations*.
- **Data Science & Social Research (DSSR), 5th International Conference**, Pescara, Italy, 19–21 February 2025.
- **DAMOCLES 2024**, workshop within AVI '24, Arenzano, Italy, 4 June 2024.
- **ICPM Doctoral Consortium**, within the 4th International Conference on Process Mining, Bolzano, Italy, 23–28 October 2022.
- **10th International Workshop on DEClarative, DECision and Hybrid Approaches to Processes (DEC2H 2022)**, within BPM 2022, Münster, Germany, 11–16 September 2022.

### Reviewing and Scientific Service

- Reviewer, **Commit2Data: Big Data Handling, Analytics & Applications 2023** — [commit2data.nl](https://commit2data.nl/en/)
- Sub-reviewer, **5th 2023 International Conference on Computer Systems and Communication Technology** — [iccsct.org](http://www.iccsct.org/)
- Sub-reviewer, **18th International Working Conference on Variability Modelling of Software-Intensive Systems (VaMoS 2024)** — [vamosconf.net/2024](https://vamosconf.net/2024)
- Member, **Artifact Evaluation Committee for QEST + FORMATS 2024** — [qest-formats.org/artifacts.html](https://www.qest-formats.org/artifacts.html)

### Visiting Position Abroad

- Two-week visiting appointment at the Technical University of Denmark (DTU), December 2022, invited by Prof. Alberto Lluch Lafuente.
The work conducted during the visit contributed to the article *White-box validation of quantitative product lines by statistical model checking and process mining*.

---

## Advanced Training and Specialisation Schools

- **Course on Public Policy Impact Evaluation, 4th edition** — Fondazione Bruno Kessler–IRVAPP, online, 3–24 March 2026.
- **Lipari School on Computational Complex and Social Systems:** *Generative AI, Human Decision and Machine Prediction: Models, Algorithms, Platforms and Ethics*, Lipari, Italy, 14–20 July 2024.
- **PhD School on Artificial Intelligence and Cybersecurity** — Sapienza University of Rome, online, December 2023.
- **PhD AI & Society 2022 Summer School** — Pisa, Italy, 4–8 July 2022.

---

## Additional Skills and Information

### Technical Skills

- **Programming and data tools:** Very good command of Python for data processing, NLP/ML pipelines, and automation scripts; good command of R for statistical analysis of survey and panel data; good command of SQL/PostgreSQL, with familiarity with Hive and Impala.
- **AI/ML and NLP:** Very good knowledge of machine learning and NLP, including Transformer-based modelling, experiment design, model evaluation, and experiment management; good command of PyTorch and good working knowledge of Hugging Face tooling.
- **LLM workflows:** Good knowledge of LLM-based workflows and tool use, including LangChain- and OpenAI API-based pipelines, retrieval, function calling, prompt design, evaluation, and robustness testing.
- **Scientific Python stack:** Good knowledge of pandas, NumPy, matplotlib, and scikit-learn.
- **Data acquisition:** Experience developing web-scraping and online data-collection pipelines, including USPTO patent scraping, YouTube crawling, and reusable scripts for online data acquisition.
- **Web development:** Good command of Flask and Django; experience with PostgreSQL-backed applications and Heroku deployment.
- **Reproducibility and collaboration:** Good command of Docker, very good experience with Git/GitHub, good knowledge of Linux, and experience with MLflow.
- **Modelling and simulation:** Agent-based modelling and discrete-event simulation using RisQFLan, QFLan, SCEL, SimPy, and Mesa.
- **Geospatial workflows:** openEO, Copernicus Earth Observation workflows, and Sentinel Hub Evalscript.
- **Methods:** Process Mining, Statistical Model Checking, benchmark design, reproducible experimental pipelines, annotation guideline design, data labelling, and dataset curation and validation.
- **Productivity tools:** Very good command of Microsoft Word, Excel, and PowerPoint.

### Languages

- **Italian:** Native.
- **English:** C1 overall, with C2-level listening comprehension.

### Interpersonal and Communication Skills

- Excellent communication skills in Italian and English, including stakeholder-oriented reporting and international research experience.
- Excellent ability to work both collaboratively and independently in interdisciplinary and international teams.
- Strong scientific writing and dissemination skills, including experience producing annotation guidelines and evaluation protocols.
- Teaching and mentoring experience, including three years of hands-on Machine Learning teaching in Python-based laboratories.

### Organisational Skills

- Excellent organisational skills developed while coordinating study and work commitments in London between 2014 and 2020.
- Excellent deadline-management skills developed while working simultaneously in two roles at Goldsmiths Library in 2019 and attending the MSc in Data Science.

### Certifications

- **DeepLearning.AI TensorFlow Developer** — DeepLearning.AI on Coursera, 10 January 2021. Courses: Introduction to TensorFlow for AI/ML/DL; Convolutional Neural Networks in TensorFlow; Natural Language Processing in TensorFlow; Sequences, Time Series and Prediction.
- **Learning Django** — LinkedIn Learning, 15 December 2020.
- **Advanced NLP with Python for Machine Learning** — LinkedIn Learning, 15 November 2020.
- **Foundations for Big Data Analysis with SQL** — Cloudera on Coursera, 25 October 2020.
- **Specialized Module on Human Health and Climate Change** — UN CC:Learn, 6 January 2018.
- **National Adaptation Plans: Building Climate Resilience in Agriculture** — UN CC:Learn, 1 November 2017.

