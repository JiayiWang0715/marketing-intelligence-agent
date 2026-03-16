# AI Marketing Intelligence Pipeline

An AI-driven system for analyzing advertisement datasets and extracting structured marketing strategy insights.

## Overview

This project implements a modular pipeline that processes advertisement images and metadata to generate structured marketing intelligence. The system combines image feature extraction, text analysis, clustering-based strategy discovery, and automated analytics.

The pipeline converts raw advertisement data into structured insights that can support marketing analysis and strategic decision-making.

## My Contribution

I served as the primary developer for the data processing, strategy clustering, analytics, and retrieval-based analysis components of the system.

My work focused on:

* designing the overall pipeline workflow
* implementing data processing and storage
* building clustering-based marketing strategy discovery
* integrating a retrieval-based assistant for querying marketing insights

Some modules such as image feature extraction and basic NLP preprocessing were implemented as part of the broader system architecture.

## System Pipeline

The system processes advertisement data through the following stages:

1. **Data Collection**

   * Load annotated advertisement metadata from JSON files.

2. **Image Feature Enrichment**

   * Extract OCR text from images.
   * Analyze layout and visual features.
   * Extract dominant color features.

3. **Data Storage**

   * Store enriched data in a SQLite database for efficient querying.

4. **Strategy Discovery**

   * Apply clustering methods to identify recurring marketing strategies across advertisements.

5. **Analytics**

   * Generate structured insights on marketing patterns.

6. **Retrieval-based Analysis**

   * Use a retrieval pipeline to support natural-language queries over the marketing dataset.

## Tech Stack

* Python
* pandas
* scikit-learn
* SQLite
* pytesseract (OCR)
* OpenCV
* LLM-based analysis (RAG prototype)

## Project Structure

cv/
Image feature extraction modules (OCR, layout analysis, color extraction)

nlp/
Text preprocessing and sentiment analysis modules

strategy_clustering/
Clustering algorithms for identifying marketing strategy patterns

analytics/
Statistical analysis and dataset insights

rag/
Retrieval-based assistant for querying marketing insights

database/
SQLite data storage scripts

data/
Processed advertisement datasets

## Example Output

The system can automatically identify patterns such as:

* common visual design strategies across campaigns
* dominant marketing themes in different industries
* correlations between visual style and sentiment
