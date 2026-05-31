# Neural Similarity Learning for Dysarthric Cross-Lingual and Multilingual Speaker Verification

## Overview

Modern Automatic Speaker Verification (ASV) systems perform well under normal speech conditions but degrade significantly when speech is affected by neurological disorders such as dysarthria or when enrollment and testing occur across different languages.

This project investigates the robustness of ECAPA-TDNN-based speaker verification under:

* Monolingual verification
* Cross-lingual verification
* Multilingual verification
* Dysarthric speech conditions

and evaluates whether a learned neural similarity backend can outperform traditional cosine similarity scoring.

## Research Question

How reliable are modern speaker verification systems when faced with pathological speech and language mismatch?

Can a learned similarity function improve robustness compared to conventional geometric scoring methods?

## Key Findings

* Neural similarity learning reduced Equal Error Rate (EER) from 10.9% to 6.5% under normal speech conditions.
* Dysarthric speech substantially increased verification difficulty.
* Cross-lingual evaluation produced higher error rates than monolingual settings.
* Multilingual dysarthric verification was the most challenging scenario, reaching 15.7% EER.
* Learned similarity scoring consistently outperformed cosine similarity across all configurations.

## Method

### Embedding Extraction

* ECAPA-TDNN speaker embeddings

### Backend Comparison

Baseline:

* Cosine Similarity

Proposed:

* Neural Similarity Learning Backend
* Absolute Difference Features
* Element-wise Product Features
* Multi-Layer Perceptron Scoring

### Evaluation

* Equal Error Rate (EER)
* Detection Error Tradeoff (DET) Curves

## Why This Work Matters

Most speaker verification research assumes healthy speech and matched language conditions.

Real-world systems must operate under variability, impairment, and distribution shift.

This work studies robustness as a first-class problem and highlights failure modes that emerge when pathological speech and multilingual conditions interact.

## Future Directions

* Severity-aware modeling
* Transformer-based speaker embeddings
* Domain adaptation techniques
* Pathology-aware representation learning
* Reliability-aware verification systems

## Manuscript

The full manuscript is currently under submission and is not publicly distributed.

A detailed project overview, methodology, experimental findings, and research notes are provided in this repository.

Full manuscript available upon request.

