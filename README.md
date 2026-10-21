# Applied Natural Language Processing for Online Harm Detection

**Universität Konstanz, Winter Semester 2026/27**
Thursdays, 15:15–16:45, C422

**Instructor:** Miriam Schirmer (miriam.schirmer@uni-konstanz.de)
**Office hours:** by appointment; please email to arrange a time
**Course type:** MA S / PhD S, taught in English

---

## About the course

This seminar covers the application of natural language processing (NLP) and large language model (LLM) methods to detect and analyze harmful online discourse, such as hate speech and hostile rhetoric. Topics include text classification, topic modeling, large-scale social media data analysis, and approaches for adapting pre-trained models and LLMs to domain-specific tasks. At the center of the course is an independent research project: students work with real data on a question of their own choosing and present their results in two presentations and a final report. We will be working with Python. No prior programming experience is required.

After an introductory session, the course has three parts. Part 1 is a crash course in NLP (sessions 2 to 4). Part 2 consists of three applied practicals followed by mid-term project presentations (sessions 5 to 9). Part 3 covers advanced topics and project work and ends with the final project presentations (sessions 10 to 14). In the practicals, we work with pre-built Python notebooks in Google Colab.

### Learning objectives

By the end of the course, students will be able to:

- apply NLP methods to real-world data on harmful online discourse;
- navigate the key methodological and ethical challenges in this area;
- independently design and carry out a small-scale computational research project.

---

## Schedule

| Session | Date | Type | Topic | Materials |
|:-------:|:----:|:----:| ----- | --------- |
| 1 | 22 Oct | ![Intro](https://img.shields.io/badge/Intro-lightgrey?style=flat-square) | [Course overview](#session-1-22-october-introduction) | [Slides](slides/01_Introduction.pdf) |
| **Part 1: NLP Crash Course** | | | | |
| 2 | 29 Oct | ![Theory](https://img.shields.io/badge/Theory-4C72B0?style=flat-square) | [Text as data and defining online harm](#session-2-29-october-text-as-data-and-defining-online-harm) |  |
| 3 | 05 Nov | ![Theory](https://img.shields.io/badge/Theory-4C72B0?style=flat-square) | [Supervised classification](#session-3-5-november-supervised-classification) |  |
| 4 | 12 Nov | ![Theory](https://img.shields.io/badge/Theory-4C72B0?style=flat-square) | [Transformers and LLMs](#session-4-12-november-transformers-and-llms) |  |
| **Part 2: Applications** | | | | |
| 5 | 19 Nov | ![Practical](https://img.shields.io/badge/Practical-55A868?style=flat-square) | [Topic modeling with BERTopic (project idea due)](#session-5-19-november-practical-topic-modeling-with-bertopic) |  |
| 6 | 26 Nov | ![Practical](https://img.shields.io/badge/Practical-55A868?style=flat-square) | [Automated fact-checking](#session-6-26-november-practical-automated-fact-checking) |  |
| 7 | 03 Dec | ![Practical](https://img.shields.io/badge/Practical-55A868?style=flat-square) | [Polarization](#session-7-3-december-practical-polarization) |  |
| 8 | 10 Dec | ![Presentations](https://img.shields.io/badge/Presentations-DD8452?style=flat-square) | [Mid-term presentations I](#session-8-10-december-mid-term-presentations-i) |  |
| 9 | 17 Dec | ![Presentations](https://img.shields.io/badge/Presentations-DD8452?style=flat-square) | [Mid-term presentations II](#session-9-17-december-mid-term-presentations-ii) |  |
|  | 24 and 31 Dec |  | *Winter break, no sessions* |  |
| **Part 3: Advanced Topics and Projects** | | | | |
| 10 | 07 Jan | ![Discussion](https://img.shields.io/badge/Discussion-8172B3?style=flat-square) | [Ethics of online harm research](#session-10-7-january-ethics-of-online-harm-research) |  |
| 11 | 14 Jan | ![Project lab](https://img.shields.io/badge/Project%20lab-937860?style=flat-square) | [Project lab or guest project presentation](#session-11-14-january-project-lab-or-guest-project-presentation) |  |
| 12 | 21 Jan | ![Project lab](https://img.shields.io/badge/Project%20lab-937860?style=flat-square) | [Project lab](#session-12-21-january-project-lab) |  |
| 13 | 28 Jan | ![Presentations](https://img.shields.io/badge/Presentations-DD8452?style=flat-square) | [Final presentations I](#session-13-28-january-final-presentations-i) |  |
| 14 | 04 Feb | ![Presentations](https://img.shields.io/badge/Presentations-DD8452?style=flat-square) | [Final presentations II](#session-14-4-february-final-presentations-ii) |  |
|  | mid-Feb or end of Mar | ![Deadline](https://img.shields.io/badge/Deadline-C44E52?style=flat-square) | [Project report due](#3-final-report-70) |  |

---

## Research project and assessment

Assessment is based on your research project and consists of three parts.

### 1. Mid-term presentation (15%)

10 or 17 December 2026, in class. You present your research question, your data and the method you plan to use, and you receive feedback before the winter break.

### 2. Final presentation (15%)

28 January or 4 February 2027, in class. You present your results.

### 3. Final report (70%)

Deadline: either mid-February or end of March; you commit to a date during your first project presentation.

### Groups and grading

Projects can be done individually or in pairs (groups of three on request). Please submit a short project idea, and the names of your group members if you work in a group, by **19 November**.

Each group receives one shared grade for the mid-term presentation, the final presentation and the report. Groups may divide the work as they see fit, but all members are expected to understand the entire project, to present and to answer questions. During the discussion, questions may be addressed to any group member about any part of the project. Reports should include a brief statement of each member's contributions.

Presentations are assessed as a whole using the following criteria:

| Criterion | What we look at |
| --------- | --------------- |
| Research question and motivation | Clear, relevant and grounded in the literature |
| Data and method | Suited to the question; choices are explained |
| Results | Correctly interpreted, limitations named |
| Presentation | Structure, clarity, timing |
| Discussion | Questions are moderated by the group |

---

## Weekly content and readings

Each session of the crash course has two prep readings: a chapter from Jurafsky and Martin's textbook *Speech and Language Processing* (3rd edition draft, [freely available online](https://web.stanford.edu/~jurafsky/slp3/)) and an article on online harm. Please read both before the session. Readings for the later sessions will be announced during the semester. All readings are freely accessible.

### Session 1 (22 October). Introduction

This session introduces the course.

### Part 1: NLP Crash Course

#### Session 2 (29 October). Text as data and defining online harm

**Readings:**

- **[pp. 1–24]** Jurafsky, D. & Martin, J.H. (2026). Words and Tokens. *Speech and Language Processing*. 3rd ed. draft, ch. 2. https://web.stanford.edu/~jurafsky/slp3/2.pdf
- Fortuna, P. & Nunes, S. (2018). A Survey on Automatic Detection of Hate Speech in Text. *ACM Computing Surveys* 51 (4): 1–30. https://dl.acm.org/doi/pdf/10.1145/3232676

#### Session 3 (5 November). Supervised classification

How can computers learn categories from examples? This session covers supervised classification, the annotation of training data and evaluation with precision, recall and F1. We pay special attention to problems typical of harm detection: rare classes, disagreement between annotators and biased datasets.

**Readings:**

- Jurafsky, D. & Martin, J.H. (2026). Logistic Regression and Text Classification. *Speech and Language Processing*. 3rd ed. draft, ch. 4. https://web.stanford.edu/~jurafsky/slp3/4.pdf
- Vidgen, B. & Derczynski, L. (2020). Directions in abusive language training data, a systematic review: Garbage in, garbage out. *PLOS ONE* 15 (12): e0243300. https://doi.org/10.1371/journal.pone.0243300

#### Session 4 (12 November). Transformers and LLMs

How do modern language models represent meaning? This session covers embeddings, the intuition behind attention and pre-trained models such as BERT, and how to use them through Hugging Face. We end with prompting and zero-shot classification with LLMs.

**Readings:**

- Jurafsky, D. & Martin, J.H. (2026). Transformers and Pretraining. *Speech and Language Processing*. 3rd ed. draft, ch. 7. https://web.stanford.edu/~jurafsky/slp3/7.pdf
- Plaza-del-Arco, F.M., Nozza, D. & Hovy, D. (2023). Respectful or Toxic? Using Zero-Shot Learning with Language Models to Detect Hate Speech. *Proceedings of the 7th Workshop on Online Abuse and Harms (WOAH)*, pp. 60–68. https://aclanthology.org/2023.woah-1.6/

### Part 2: Applications

#### Session 5 (19 November). Practical: Topic modeling with BERTopic

#### Session 6 (26 November). Practical: Automated fact-checking

#### Session 7 (3 December). Practical: Polarization

#### Session 8 (10 December). Mid-term presentations I

#### Session 9 (17 December). Mid-term presentations II

*Winter break: no sessions on 24 and 31 December.*

### Part 3: Advanced Topics and Projects

#### Session 10 (7 January). Ethics of online harm research

#### Session 11 (14 January). Project lab or guest project presentation

Time to work on your projects, with individual consultations.

#### Session 12 (21 January). Project lab

Time to work on your projects, with individual consultations.

#### Session 13 (28 January). Final presentations I

Groups present the results of their projects.

#### Session 14 (4 February). Final presentations II

Continuation of the final presentations and wrap-up of the course.

---

## Materials

- **Slides** are linked in the schedule above after each session and stored in [`slides/`](./slides).
- **Notebooks** for the practicals are stored in [`notebooks/`](./notebooks). Each one has an *Open in Colab* link, so they run in your browser without installing anything.

<!--
How to add materials (this comment is not shown on GitHub):
1. Export the slides from PowerPoint as PDF (File > Export > PDF), name them like 02_Text_as_Data.pdf
   and upload them to slides/.
2. Upload notebooks to notebooks/, e.g. notebooks/03_Preprocessing.ipynb.
3. In the schedule table, fill the Materials cell of that session, for example:
   [Slides](slides/02_Text_as_Data.pdf)
   [Notebook](notebooks/03_Preprocessing.ipynb) [Open in Colab](https://colab.research.google.com/github/MiriamSchirmer/online-harm-nlp-ws2627/blob/main/notebooks/03_Preprocessing.ipynb)
-->
