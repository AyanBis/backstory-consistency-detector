# Backstory Consistency Detector

This project was developed for the **Kharagpur Data Science Hackathon (KDSH 2026)** to address the challenge of evaluating whether a hypothetical character backstory is logically and causally consistent with a long-form narrative.

The system performs long-context reasoning over entire novels to determine whether a proposed past can plausibly produce an observed future.

---

## Problem Overview

Large language models often struggle with global reasoning across long narratives. They may produce locally plausible explanations but fail to maintain consistency over time.

This project treats the task as a structured classification problem:

**Given:**
- A complete novel (100k+ words)
- A hypothetical character backstory

**Goal:**
- Determine whether the backstory is consistent with the narrative
- Evaluate causal compatibility and constraint adherence

---

## Key Challenges Addressed

- Long-context narrative reasoning
- Evidence aggregation across large texts
- Causal consistency tracking
- Constraint-aware classification
- Hybrid NLP and machine learning approaches

---

## Repository Structure

    backstory-consistency-detector/
    ├── models/
    │   ├── KDSH Track A Model.ipynb
    │   └── KDSH Track B Model.ipynb
    ├── data/
    │   ├── train.csv
    │   ├── test.csv
    │   ├── In search of the castaways.txt
    │   └── The Count of Monte Cristo.txt
    ├── results/
    │   ├── results_track_a.csv
    │   └── results_track_b.csv
    ├── docs/
    │   └── Hackathon reports and problem statement
    ├── requirements.txt
    └── README.md

---

## Models Included

### Track A — Systems Reasoning with NLP

- Transformer-based embeddings
- Long-context retrieval pipeline
- Classification using similarity scoring
- Pathway framework integration

### Track B — Continuous Narrative Reasoning

- Enhanced representation learning
- Incremental context tracking
- Improved causal reasoning over narrative flow
- Hybrid ML + LLM architecture

---

## How to Run

Install dependencies:

    pip install -r requirements.txt

Open and run the notebooks inside the **models** folder.

---

## Results

The models demonstrate strong capability in detecting narrative inconsistencies by leveraging long-context reasoning and causal analysis across distributed textual evidence.

---

## Hackathon

Kharagpur Data Science Hackathon 2026  
Track A and Track B submissions

---

## Author

Ayan Biswas  
AI/ML Researcher | Founder of Infiltrix

