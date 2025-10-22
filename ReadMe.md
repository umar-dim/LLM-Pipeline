# LLM Pipeline

Project: LLM Pipeline | Scala, Apache Spark, Hadoop MapReduce, DeepLearning4j, AWS EMR

November 2024

## Overview

This repository contains an end-to-end LLM data processing and training pipeline implemented in Scala. The project demonstrates building scalable, distributed NLP preprocessing and embedding workflows using Apache Spark and Hadoop MapReduce, training components with DeepLearning4j, and deployment/monitoring on AWS EMR.

## Key contributions

- Engineered a distributed data processing pipeline for large-scale NLP using Spark and MapReduce, parallelizing tokenization, vocabulary construction, and embedding generation.
- Designed modular software components adhering to OOP and MVC principles for improved scalability and maintainability.
- Deployed and monitored distributed training jobs on AWS EMR, ensuring efficient resource management and fault tolerance.
- Applied data-driven optimization using machine learning techniques to evaluate semantic accuracy and model performance.

## Repository layout

- `LLM-Training/`: Spark-based training, token embeddings generator, and training harness.
- `Token-Processor/`: MapReduce and Spark jobs for tokenization, token counts, BPE/token merging, and embedding map-reduce jobs.

## Technologies

- Scala
- Apache Spark
- Hadoop MapReduce
- DeepLearning4j
- AWS EMR

## Quick start

See the individual module READMEs for build and run instructions:

- `LLM-Training/Readme.md` — Spark training and embedding generation details.
- `Token-Processor/README.md` — MapReduce and token processing jobs.
