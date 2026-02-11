---
layout: default
title: Projects
permalink: /projects/
---
# Projects

Here are some of the things I've worked on. Some have been as part of research as a grad student, some were just for fun!

My GitHub is [spacekaila](https://github.com/spacekaila).

## Ravellm ([repo](https://github.com/spacekaila/ravellm))

A recommender system powered by retrieval-augmented generation (RAG). I've been knitting since I was 6 and by far the hardest part is picking my next project. Ravellm uses NLP to recommend knitting patterns by embedding and retrieving pattern metadata from the Ravelry pattern database. I designed data ingestion and validation pipelines with data deduplication and incremental updates to a vector database. It uses an open source LLM model to then generate personalized, explainable recommendations. *Tech*: Python, SentenceTransformer, ChromaDB, LangChain, Mistral 7B.

## Will I Be Depressed ([repo](https://github.com/spacekaila/will-i-be-depressed))

I live in a place with very long, cold, and depressing winters. So I wrote a program that pulls weather data from the National Weather Service API and tells you if you'll be depressed. To escape depression, it has to be sunny or clear, chance of rain < 15%, temperature >= 60 F, and wind <= 18 mph (I have long hair).

## McFACTS ([repo](https://github.com/mcfacts/mcfacts))

This project formed the bulk of my PhD. McFACTS is an open source Monte Carlo Python framework for statistical modeling. As one of the lead developers, I designed and implemented data processing pipelines for synthetic populations of 900K+ objects with comprehensive validation frameworks to reduce incidence rates of missing and incorrect data. I reduced the computational runtime by over 80% through algorithmic optimization, vectorization, and object-oriented refactoring (in my first 6 months!). I organized and led a 6-person hack week to prepare the code for production where we established standards, defined the minimal viable product (MVP) and refactored for readability. I also built an automated data visualization suite to generate publication-ready figures and videos from simulation outputs. *Tech*: Python, Numpy, Scipy, Astropy.

## Modeling population demographics ([paper](https://www.aanda.org/articles/aa/full_html/2025/02/aa51531-24/aa51531-24.html))

I developed a Python-based statistical filtering and classification pipeline to process and analyze high-dimensional datasets of 10M+ records. I performed multi-dimensional parameter space analysis to identify rare events, patterns, and relationships in the data. I then used my insights to build predictive models using Monte Carlo simulations and delay-time distribution modeling. I created comprehensive data visualizations to communicate my findings, working with an international team of researchers in a fast-paced, deadline driven environment. This project was a result of the 2023 Kavli Summer Program in Astrophysics, held at the Max Planck Institute for Astrophysics in Garching, Germany.

## what are you doing? (wayd) ([repo](https://github.com/spacekaila/wayd))

A simple python script that uses launchd to pop up a box every 15 minutes asking what you're doing. The input and time is written to a markdown file. If a date-stamped file doesn't already exist, it creates a new file with a little template. You can keep the file open and add to it manually as well, giving you a daily rundown of what you did and what you thought about.
