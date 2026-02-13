<div align="center">


# Zerui Wang

### `AI Engineer` | `PhD, Computer Engineering` | `Explainable AI Researcher`

*Building AI systems that see, understand, and explain themselves.*

[![Portfolio](https://img.shields.io/badge/Portfolio-www.xaiport.com-000000?style=for-the-badge&logo=vercel&logoColor=white)]([https://xaiport.com/](https://www.xaiport.com/))
[![Google Scholar](https://img.shields.io/badge/Scholar-12_Papers_|_101_Citations-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=QQpnwdoAAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zerui/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wangzerui418@gmail.com)

</div>

---

## About Me

I'm a researcher and engineer working at the frontier of **Explainable AI (XAI)** and **Video Understanding**. My mission is straightforward: AI systems that make consequential decisions should be able to tell us *why*.

I hold a **PhD in Computer Engineering** from Concordia University (Montreal), where I developed novel methods for interpreting video Transformer models, exposing their vulnerabilities, and deploying explainability at scale. I now work as a **Core AI Engineer at Maket Technologies**, leading explainable AI systems for generative AI applications.

My research spans three pillars:

> **Interpret** &mdash; How do video Transformers actually make decisions? (STAA)
>
> **Stress-test** &mdash; Can we break them to understand their limits? (Adversarial Attacks)
>
> **Operationalize** &mdash; How do we ship explainability into production? (XAIport / XAIpipeline)

---

## Featured Research

<table>
<tr>
<td width="50%">


### STAA &mdash; Real-Time Video Explanations

**IEEE Access 2025** &nbsp; `Q1, IF: 3.6`

A single-forward-pass method that produces spatio-temporal explanations for video Transformers with **<3% overhead**. Outperforms Grad-CAM and Attention Rollout with **0.87 faithfulness** on Kinetics-400.

> *"Why did the model classify this action?"* &mdash; answered in real time.

[![Paper](https://img.shields.io/badge/Paper-IEEE_Access-blue?style=flat-square)](https://doi.org/10.1109/ACCESS.2025.3575440)
[![arXiv](https://img.shields.io/badge/arXiv-2411.00630-b31b1b?style=flat-square)](https://arxiv.org/abs/2411.00630)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/ZeruiW/STAA)

</td>
<td width="50%">

### XAIport &mdash; XAI in Your MLOps Pipeline

**ICSE 2024** &nbsp; `A* Conference, ~20% acceptance`

A microservice framework that shifts explainability from post-hoc afterthought to an **integral development practice**. Works across Azure, GCP, and AWS out of the box.

> *Explainability shouldn't be the last step. It should be every step.*

[![Paper](https://img.shields.io/badge/Paper-ACM_DL-blue?style=flat-square)](https://doi.org/10.1145/3639476.3639759)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/ZeruiW/XAIport)
![Citations](https://img.shields.io/badge/Citations-11-green?style=flat-square)

</td>
</tr>
<tr>
<td width="50%">

### Adversarial Attacks on Video Transformers

**ACM TOMM 2025** &nbsp; `Q1, IF: 6.0`

First joint spatio-temporal adversarial attack framework targeting video Transformer self-attention. Achieves **state-of-the-art attack success rate** on Kinetics-400, revealing systematic security vulnerabilities.

> *To defend AI, you must first learn how to break it.*

[![Paper](https://img.shields.io/badge/Paper-ACM_DL-blue?style=flat-square)](https://doi.org/10.1145/3766071)

</td>
<td width="50%">

### Cloud XAI &mdash; Trustworthy Explanations at Scale

**IEEE Trans. Cloud Computing 2024** &nbsp; `Q1, IF: 5.95`

An open API architecture for explaining proprietary cloud AI services (Azure, GCP, AWS) **without accessing model internals**. Full provenance tracking for reproducibility.

> *You shouldn't need to see the engine to understand the car.*

[![Paper](https://img.shields.io/badge/Paper-IEEE_Xplore-blue?style=flat-square)](https://doi.org/10.1109/TCC.2024.3398609)
![Citations](https://img.shields.io/badge/Citations-12-green?style=flat-square)

</td>
</tr>
</table>

---

## Open Source

<table>
<tr>
<td>


**[XAI-Service](https://github.com/ZeruiW/XAI-Service)** &mdash; Full-stack XAI platform combining XAIport + XAIpipeline. Cloud-agnostic explainability services with REST APIs, automated workflow orchestration, and CI/CD deployment. If you work with AI on the cloud, this is for you.

</td>
</tr>
</table>

---

## Publication Record

```
12 peer-reviewed papers  |  101+ citations  |  h-index: 5  |  3-year career span (2022-2025)
```

| Venue                             | Type       | Rank                 | Papers |
| :-------------------------------- | :--------- | :------------------- | :----: |
| **ICSE**                          | Conference | CORE A*, h5: 74      |   1    |
| **IEEE Trans. Cloud Computing**   | Journal    | Q1, IF: 5.95         |   1    |
| **ACM Trans. Multimedia**         | Journal    | Q1, IF: 6.0          |   1    |
| **IEEE Access**                   | Journal    | Q1, IF: 3.6          |   1    |
| **IEEE SSE / COMPSAC / Big Data** | Conference | IEEE flagship        |   6    |
| **IEEE Computer Magazine**        | Magazine   | Flagship (co-author) |   1    |
| **CSCE**                          | Conference | Intl.                |   1    |

[![Google Scholar](https://img.shields.io/badge/Full_List-Google_Scholar-4285F4?style=flat-square&logo=google-scholar)](https://scholar.google.com/citations?user=QQpnwdoAAAAJ)

---

## Academic Service

- **Peer Reviewer**: 35+ manuscript reviews for **IEEE Transactions on Services Computing**, **Applied Intelligence**, **AAAI**, **IJCNN**, and more
- **Recognized Reviewer**: Springer Nature Official Certificate; AAAI Workshop personal acknowledgement
- **Workshop Facilitator**: CASCON 2024 &mdash; *"Develop Explainable AI Services on Cloud Computing and Open Source Models"*
- **Teaching Assistant**: Graduate courses in Software Engineering, Cloud Computing, and Distributed Systems at Concordia University
- **Professional Member**: IEEE Computer Society &bull; ACM

---

## Tech Stack

<div align="center">


`Python` `PyTorch` `TensorFlow` `Transformers` `FastAPI` `Docker` `Kubernetes`
`Azure` `GCP` `AWS` `HuggingFace` `LangChain` `RAG` `MLflow`
`React` `Next.js` `Node.js` `PostgreSQL` `MongoDB` `Redis` `Git`

</div>

---

## Education

| Degree                              | Institution                  | Focus                                                   |
| :---------------------------------- | :--------------------------- | :------------------------------------------------------ |
| **PhD**, Computer Engineering       | Concordia University, Canada | Explainable AI, Video Understanding, Transformer Models |
| **MSc**, Process System Engineering | TU Dortmund, Germany         | Advanced Modelling, Distributed Systems                 |
| **BSc**, Process System Engineering | CUMT, China                  | Foundation Engineering                                  |

Also: **PMP Certified** (PMI #2256006)

---

<div align="center">


*"The measure of intelligence is not whether a machine can think &mdash; but whether it can explain its thinking."*

**If you're working on interpretable AI, trustworthy ML, or video understanding &mdash; let's talk.**

[![GitHub followers](https://img.shields.io/github/followers/ZeruiW?style=social)](https://github.com/ZeruiW)
[![GitHub stars](https://img.shields.io/github/stars/ZeruiW?style=social)](https://github.com/ZeruiW)

</div>
