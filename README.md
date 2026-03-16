# AI Marketing Intelligence Pipeline

An end-to-end AI system that extracts structured marketing insights from advertisement datasets.

## Overview

This project builds a full pipeline for transforming raw advertisement images and metadata into structured marketing intelligence.

The system integrates computer vision feature extraction, natural language processing, strategy clustering, and analytics to identify recurring marketing strategies across advertisement campaigns.

## My Role

I served as the primary developer responsible for building the core data processing pipeline, clustering workflow, and analytics components.

My work included:

* designing the end-to-end data pipeline
* implementing dataset construction and storage
* developing clustering workflows to identify marketing strategy patterns
* integrating analytics and retrieval-based querying

## System Architecture

The pipeline processes advertisement data through the following stages:

1. Data collection from annotated JSON advertisement datasets
2. Image feature extraction (OCR, layout analysis, dominant color features)
3. Text processing and sentiment analysis
4. Dataset construction and storage in SQLite
5. Strategy clustering to identify recurring marketing patterns
6. Analytics and insight generation
7. Retrieval-based querying over marketing strategy insights

## Technologies

Python
pandas
OpenCV
pytesseract OCR
scikit-learn clustering
SQLite
LLM-based retrieval assistant

## Example Pipeline

The full pipeline can be executed through the following notebooks:

* build_master_dataset.ipynb
* run_cv_pipeline.ipynb
* run_nlp_pipeline.ipynb
* run_clustering.ipynb
* run_database_pipeline.ipynb
* run_full_pipeline.ipynb

## Applications

This system demonstrates how AI pipelines can transform unstructured marketing data into structured strategic insights.
