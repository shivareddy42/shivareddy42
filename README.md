<!-- ────────────────────────────────────────────────────────────────────────── -->
<!-- Header banner -->
<!-- ────────────────────────────────────────────────────────────────────────── -->

<a href="https://shivareddy42.github.io">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,55:1f1f1f,100:dc2626&height=220&section=header&text=Shiva%20Reddy%20Peddireddy&fontColor=fafafa&fontSize=44&fontAlignY=36&desc=Software%20Engineer%20%E2%80%A2%20Machine%20Learning%20Systems%20%E2%80%A2%20AI%20Safety%20Research&descSize=17&descAlignY=58&descAlign=50&animation=fadeIn" alt="header"/>
</a>

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3400&pause=900&color=DC2626&center=true&vCenter=true&width=860&height=42&lines=Building+production+machine+learning+systems+that+ship;Researching+adversarial+safety+in+agentic+AI;MS+Computer+Science+%40+UCF+%E2%80%A2+4.0+GPA+%E2%80%A2+Class+of+2026;If+it+breaks+at+2am+I+want+to+know+why+first)

<br/>

<a href="https://shivareddy42.github.io"><img src="https://img.shields.io/badge/Portfolio-DC2626?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/shivareddy42"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:shivareddy761005@gmail.com"><img src="https://img.shields.io/badge/Email-fafafa?style=for-the-badge&logo=gmail&logoColor=DC2626" alt="Email"/></a>
<a href="https://github.com/shivareddy42"><img src="https://img.shields.io/badge/GitHub-171717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## About

I am a Software Engineer focused on **machine learning systems in production** and **adversarial safety research in agentic AI**. Currently shipping ML at **BeOne Medicines** while finishing my MS in Computer Science at **the University of Central Florida** with a 4.0 GPA. I previously spent two years at **Baantics Solutions** building deep learning systems across computer vision, NLP, and recommendation workloads.

My independent research investigates what happens when LLM agents hold OAuth scopes into 5 to 15 enterprise systems at once. The transitive privilege graph of that federated scope is dramatically larger than any single declared scope, and current agent safety benchmarks do not measure it. Most of my open source work is downstream of that question.

I care about clean abstractions, measurable safety properties, and code that holds up under real production load.

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## Experience

### Software Engineer, ML and AI Systems
*BeOne Medicines · May 2024 to Present*

Building machine learning and deep learning pipelines that ship to internal product surfaces. Working across model training, evaluation harnesses, inference orchestration, and the data infrastructure that feeds them.

### Graduate Teaching Assistant
*University of Central Florida · August 2025 to May 2026*

Supporting Dr. Ali Alkinoon's graduate Computer Networks course. Previously a teaching assistant for CAP5151 (IoT Security).

### Software Engineer, Machine Learning and Deep Learning
*Baantics Solutions · May 2022 to June 2024*

Two years shipping production ML across computer vision, natural language processing, and recommendation systems. Built end to end pipelines covering data ingestion, model training, evaluation, and deployment on AWS infrastructure.

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## TRUSTFALL

<div align="center">

<a href="https://github.com/shivareddy42/trustfall-poc">
  <img src="https://raw.githubusercontent.com/shivareddy42/trustfall-poc/main/visuals/renders/01-hero.png" width="100%" alt="TRUSTFALL"/>
</a>

</div>

<br/>

An adversarial benchmark for evaluating LLM agent safety across composed enterprise system integrations. Every major agent safety benchmark today evaluates agents on a single tool surface. Real enterprise deployments do not look like that, and **TRUSTFALL** measures what happens when agents have scopes across multiple systems with realistic governance, approval chains, and referential cascades.

The headline result is a frontier lab API model approving a **$62,000 purchase order** on forged authority injected into a user record `name` field. The model quoted the injection back as if it were authoritative policy.

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Headline%20Failure-%2462%2C000%20PO%20Approved-DC2626?style=for-the-badge&labelColor=0a0a0a" alt="Headline Result"/>
<img src="https://img.shields.io/badge/Attack%20Surface-5%20of%2030%20Scenarios-7a1818?style=for-the-badge&labelColor=0a0a0a" alt="Attack Surface"/>
<img src="https://img.shields.io/badge/API%20Spend-Under%20%245-fafafa?style=for-the-badge&labelColor=0a0a0a&logoColor=DC2626" alt="API Spend"/>

<br/><br/>

<a href="https://shivareddy42.github.io/trustfall-poc/Landing.html"><img src="https://img.shields.io/badge/Open%20Live%20Dashboard-DC2626?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Demo"/></a>
<a href="https://github.com/shivareddy42/trustfall-poc"><img src="https://img.shields.io/badge/View%20Source-171717?style=for-the-badge&logo=github&logoColor=white" alt="Source"/></a>
<a href="https://github.com/shivareddy42/trustfall-poc/blob/main/report/findings.md"><img src="https://img.shields.io/badge/Read%20Findings-fafafa?style=for-the-badge&logo=readthedocs&logoColor=DC2626" alt="Findings"/></a>

</div>

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## Selected Projects

*TRUSTFALL is one of several projects I have shipped. A handful of others are below.*

<br/>

**[mirage](https://github.com/shivareddy42/mirage)** · Text to video generation pipeline. LLM scene planning, Stable Diffusion keyframes with batched CUDA inference and torch.compile, RIFE interpolation, FFmpeg assembly. Achieves a 7.2x speedup over the naive baseline. Gradio frontend backed by a Redis job queue.

**[inference-server](https://github.com/shivareddy42/inference-server)** · Low latency model serving built on FastAPI. Dynamic batching, multi backend support across PyTorch, ONNX, and TensorRT, Kubernetes deployment manifests, and Prometheus metrics. Designed to serve real production traffic under sub 100ms SLOs.

**[ml-training-profiler](https://github.com/shivareddy42/ml-training-profiler)** · Drop in profiler for PyTorch training loops. Surfaces bottlenecks across data loading, forward, backward, and optimizer steps. Bundled benchmarks for AMP, torch.compile, gradient checkpointing, and CUDA graph capture.

**[distributed-ids](https://github.com/shivareddy42/distributed-ids)** · Distributed IoT intrusion detection using federated learning. Edge clients train locally, the server aggregates with FedAvg, MQTT handles messaging, and a Streamlit dashboard surfaces threats in real time.

**[dreamforge](https://github.com/shivareddy42/dreamforge)** · Stable Diffusion image studio with a custom Gradio interface. Supports SDXL, LoRA hot swapping, and saved generation profiles for prompt engineering and parameter sweeps.

<br/>

<details>
<summary><b>More open source experiments</b></summary>

<br/>

**[GeoQuake](https://github.com/shivareddy42)** · Geospatial earthquake analytics dashboard built on deck.gl and PostGIS.

**[Crypto Strategy Arena](https://github.com/shivareddy42)** · Backtesting harness for crypto futures strategies with PnL attribution and slippage models.

**[IPL Cricket Analytics](https://github.com/shivareddy42)** · Ball by ball IPL analytics pipeline with player performance models and match outcome predictors.

</details>

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Machine Learning and AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)

**Backend and APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Infrastructure and Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

**Data and Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**DevOps and Observability**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

</div>

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shivareddy42/shivareddy42/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shivareddy42/shivareddy42/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/shivareddy42/shivareddy42/output/github-snake-dark.svg" width="100%"/>
  </picture>
</div>

<br/>

<div align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=shivareddy42&bg_color=0a0a0a&color=fafafa&line=dc2626&point=fafafa&area=true&area_color=dc2626&hide_border=true&custom_title=Commit%20Activity" alt="activity graph"/>
</div>

<br/>

<!-- ────────────────────────────────────────────────────────────────────────── -->

## Contact

<div align="center">

<p>Open to roles in machine learning engineering and AI safety.<br/>
Happy to talk about agent safety, model serving, or what breaks at 2am.</p>

<a href="mailto:shivareddy761005@gmail.com"><img src="https://img.shields.io/badge/shivareddy761005@gmail.com-DC2626?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/shivareddy42"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://shivareddy42.github.io"><img src="https://img.shields.io/badge/Portfolio-171717?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>

</div>

<a href="https://github.com/shivareddy42">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:dc2626,45:1f1f1f,100:0a0a0a&height=120&section=footer"/>
</a>
