---
pinned: true
---


# Machine Learning Zoomcamp

This is the main page for personal learning management for the DataTalksClub Machine Learning Zoomcamp. A 10-week online course that can be taken in a cohort or self-paced.

## General Overview

The purpose of this course is to not just teach the basics of Machine Learning algorithms and Deep Learning with PyTorch. Knowing the algorithms is one aspect of ML, but to truly become an ML Engineer, one needs to understand how to deploy a model in production. That is why it is split into two parts. Part one focuses on the highly technical aspect where you create a model. Part two is when you learn to containerize it in Docker, build APIs with FastAPI, and scale with Kubernetes and AWS Lambda. The goal is to gain hands-on experience through both homework and projects in end-to-end ML workflows.

## Course Topics

### Part 1

| Topic | Description | Tools |
| --- | --- | --- |
| [[Week-02-Linear Regression-Feature-Engineering/Linear Regression and Feature Engineering]] | Master feature creation, categorical variable handling, and regularization techniques | NumPy, Pandas, Scikit-Learn |
| **Classification with Logistic Regression** | Learn feature importance and model evaluation | Scikit-Learn, Matplotlib |
| **Decision Trees and Ensemble Methods** | Explore gradient boosting and XGBoost implementation | XGBoost, Scikit-Learn |
| **Neural Networks and Deep Learning** | Build CNNs and implement transfer learning | TensorFlow, PyTorch, Keras |

### Part 2

| Topic | Description | Tools |
| --- | --- | --- |
| **Model Deployment** | Move models from notebooks to services and applications | FastAPI, Pipenv, Docker |
| **Serverless Deep Learning** | Deploy models efficiently using serverless architecture | AWS Lambda, ONNX Runtime |
| **Container Orchestration** | Automate deployment, scaling, and management of containerized applications | Kubernetes, TensorFlow Serving |
| **KServe (optional)** | Advanced deployment capabilities for production ML systems | KServe |

## Tech Stack

### Part 1: ML Algorithms & Their Implementation

#### Code

- Python
- Jupyter Lab/Notebooks

#### Data Manipulation

- NumPy
- Pandas

#### Visualization

- Matplotlib
- Seaborn

#### Applying ML Algorithms

- Scikit-learn

#### Neural Networks, Deep Learning

- Tensorflow
- PyTorch

### Part 2: Model Deployment

#### Deployment

- Docker
- FastAPI
- Pipenv

#### Automated Deployment & Scaling

- Kubernetes (K8s)
- Tensorflow Serving

#### Severless Deep Learning

- AWS Lambda
- ONNX Runtime

## My Personal Motivation

The reason I registered for this course is to completely refresh my knowledge of machine learning so I can also advertise those skills on my resume. I can hopefully also use the skills I learn to start applying for Data Scientist and ML Engineer roles with some serious projects deployed and available for a recruiter/hiring manager to test out.

Also, I’ve never actually studied deep learning to any major degree. The courses available to me in my MS program at Boston University did not have a Deep Learning course. The best I got was a run through of popular machine learning algos and put together some simple projects using Jupyter Notebooks. I’ve come to realize that is far from enough in terms of demonstrating competency and experience, so I will be focusing heavily on the course to learn as much as possible about both model training, creation, and deployment.

Since my primary experience and background is as a Data Engineer, I’ll be trying to add on some aspect of that into my Midterm and Capstone projects if possible. I will look into sourcing my own data and creating an ETL pipeline along with a proper database setup that I can then use to train an ML model and deploy it using the technologies I learn in the second part of the course. I think that would be a solid illustration of truly end-to-end experience across an data stack.

## Studying Workflow

For this course, the lectures are all video-based, given that it’s over Zoom. If I can’t catch a live lecture, it will usually be uploaded to the DataTalksClub YouTube page within 24 hours. I’ll do my best to give time to attend the live lectures just in case I might have a question to ask, but if that’s not possible, I will post any questions on Slack.

I’ve found that instead of typing out notes during video lectures, I tend to focus better when I’m actually writing things down. Having a physical notebook and pen really helps me zone in and not get distracted by any notifications or the like. I can just set my Focus Mode to Study or some other DnD mode, and no notifications will pop up on my phone, tablet, or laptop.

There was a really interesting [paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11943480/) I read a year or so ago on the benefits of writing things down when learning. The most important highlight of the author’s conclusion for me was:

> Handwriting activates a broader network of brain regions involved in motor, sensory, and cognitive processing, contributing to deeper learning, enhanced memory retention, and more effective engagement with written material. Typing, while more efficient and automated, engages fewer neural circuits, resulting in more passive cognitive engagement. These findings suggest that despite the advantages of typing in terms of speed and convenience, handwriting remains an important tool for learning and memory retention, particularly in educational contexts.

[[CleanShot 2026-10-02 at 4.17.07 PM@2x.png]]

The paper included a picture of the neural correlates of handwriting and typewriting. As can be seen above, more regions of the brain lit up when the subject was writing notes by hand. Further cited studies also claimed that use of a digital interface such as tablet with handwriting capabilities (iPad Pro and Apple Pencil, in my case) still led to “…reduced involvement of the somatosensory cortex, suggesting that physical contact with paper might be a key factor in the cognitive process of handwriting.” Styluses and tablets may have come a long way, but a simple notebook seems to be the way to go for me.

However, that’s not to say that there won’t be technology involved in the note-taking process. I will be writing down everything and drawing visual representations necessary to solidify my understanding of the concepts. Upon completion of the physical note-taking, I will be digitizing it all through the use of LLMs and OCR along with a couple of simple skills to help draw out diagrams of the various drawings I create in my notebook to help convert it to a readable Markdown format. All of which will be posted in this repository for future reference.

Also, I’ve found that spaced repetition and answering quiz style questions helps me catch any gaps in my knowledge, so I will also be using a popular coding harness, Pi, to help learn the topics. I recently discovered a YouTube content creator through a video they published called [How I Use AI to Learn Things](https://youtu.be/kzcI5F4tGiU?si=1Ptm4kpRebNeLl0Z).

In it, they describe a Pi Skill that they themselves wrote to research and learn new topics. They’ve published a Github [repo](about:blank) for the skill, so I will be installing Pi Coding Agent and adding the learning skill. Let’s see what comes of it. Based on the [demo](https://youtu.be/kzcI5F4tGiU?si=sB682ebFvpYHCyy7&t=481) in the video, I have a good feeling about it. He did say in overview that it works for his style of learning, I’ll have to modify it to make sense to me. That can serve as a learning experience on the side. Let’s see how it goes.

## Repo Layout

In the Github [repo](https://github.com/DataTalksClub/machine-learning-zoomcamp) for the course, each week is separated into its own respective folder. I will be following the exact same standard in my notes repo with the main difference stemming from the titles. Each folder will have a main overview note that covers all of the topics learned and the relevant key highlights. The weekly note will be created first to act as both a planner and task list for submissions. I will be including snippets of code within my notes, but the Jupyter notebook for my assignments will also be attached.

I might also play around with a new library I was introduced to called [Marimo](https://marimo.io/) that is essentially Jupyter notebooks on steroids. Much simpler Markdown implementation of Markdown in cells (I’ve always found JN a bit finicky with edits). Interactivity within the notebook environment, which is crazy good looking if you go through their [demo notebook](https://molab.marimo.io/notebooks/nb_jJiFFtznAy4BxkrrZA1o9b/app?show-code=true). I’ll do my homework in both just to see if there’s any major difference. From my understanding, they should be roughly compatible. I’ll use an LLM to port it over, so we’ll see how it turns out.