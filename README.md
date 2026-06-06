# 💫 About Me

Final-year MEng Computer Science student at Durham University, with interests spanning software development, application security, and applied machine learning.

My dissertation investigates detecting Borderline Personality Disorder from Reddit posts using hierarchical attention networks, transformer-based language models, and clinically grounded NLP features, with a focus on balancing predictive performance with explainability. Beyond research, I enjoy building things: JSGrades is an online qualification tracker I've been developing with React and Node.js; I've built image repair pipelines using OpenCV to restore damaged X-rays; and most recently I worked on interactive geospatial tools for analysing lunar south pole landing sites for the Artemis III mission using Python and PyGMT.

Accredited Affiliate Member of the Chartered Institute of Information Security · ITIL 4 Foundation Certified

Outside of work, I'm a big Formula 1 fan and always happy to talk race strategy.

## 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/jamesduxbury03) [![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?logo=vercel&logoColor=white)](https://jamesduxbury-dot-com.vercel.app/)

## 💻 Tech Stack

#### Languages

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![Haskell](https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

#### Web

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

#### ML / NLP

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

#### Data

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Polars](https://img.shields.io/badge/polars-%23CD792C.svg?style=for-the-badge&logo=polars&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Jupyter](https://img.shields.io/badge/jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)

#### DevOps / Tools

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

## 📊 GitHub Stats

![](https://github-readme-streak-stats.herokuapp.com/?user=jsduxie&theme=dark&hide_border=false)

## 🏆 GitHub Trophies
![](https://github-profile-trophy-kappa-rose.vercel.app/?username=jsduxie&theme=nord&no-frame=false&no-bg=true&margin-w=4)

## 💻 Projects

### FG-HAN: Feature-Guided Hierarchical Attention for BPD Detection from Social Media

My MEng dissertation proposes FG-HAN, a hierarchical attention network that aligns three parallel attention heads to the interpersonal, emotional, and behavioural dimensions of Sanislow et al.'s (2000) three-factor model of BPD via additive psycholinguistic feature bias on the attention logits. The task is binary classification (BPD vs control) over Reddit posts, where subreddit membership serves as a proxy label and control communities are drawn from clinically adjacent conditions (e.g. bipolar, PTSD, CPTSD, depression) that drive real-world misdiagnosis. Crucially, FG-HAN produces explanations decomposed along the three clinical dimensions without requiring any per-factor annotation in the dataset.

- FG-HAN matched the strongest transformer baselines on classification (Macro F1 0.874) while producing significantly more specialised heads than its unguided counterpart (composed JSD 0.645 vs 0.380, p < 0.001)
- Evaluated 13 architectures from logistic regression to pretrained transformers alongside a cross-architecture faithfulness comparison of four attribution methods, finding that method choice affects faithfulness more than architecture
- **Tech:** Python, PyTorch, HuggingFace Transformers, LIWC, NRC-VAD, Empath, scikit-learn

> Code and full results to follow after examination.

---

### Artemis III Lunar South Pole Landing Site Analysis

An interactive geospatial analysis tool for evaluating candidate landing sites for NASA's Artemis III mission at the lunar south pole. Built as part of COMP4097 Advanced Visualisation, using real LOLA elevation data and illumination overlays.

- Implemented slope computation via Horn's (1981) kernel with latitude correction and TOPSIS-based multi-criteria suitability scoring across candidate sites
- Built two interactive visualisation tools using PyGMT for terrain rendering, illumination analysis, and candidate site comparison

> Code to follow after examination.

---

### Image Processing to Repair Damaged X-Rays with OpenCV

<img width="575" alt="OpenCV Workflow" src="images/opencv-workflow.png">

A pipeline to repair damaged X-ray images and improve the performance of a pretrained classifier, built with OpenCV and Python.

- Improved classifier accuracy from 0.55 (baseline) to 0.90 through noise reduction, inpainting, and edge detection techniques
- Applied Canny Edge Detection to identify missing regions and Criminisi's Inpainting Algorithm for realistic image restoration
- **Tech:** Python, OpenCV, NumPy

[Link to repo](https://github.com/jsduxie/opencv-xray-repair)

---

### Semantic Scholar Research Paper Monitor

An automated research monitoring agent that tracks new publications across specified topics using the Semantic Scholar API and generates daily digest emails summarised by Gemini AI. Built to keep on top of the BPD/mental health NLP literature during my dissertation.

- Integrates Semantic Scholar API for paper discovery with Gemini AI for summarisation and relevance filtering
- Delivers daily email digests of new and relevant papers matching configurable research interests

[Link to repo](https://github.com/jsduxie/researcher-agent)
