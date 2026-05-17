# African Clinical ASR Proposal Experiments

This repository contains code, configurations, result tables, and documentation for my PhD proposal on efficient domain adaptation of pretrained ASR models for African-accented clinical speech recognition.

## Dissertation Goal

The goal of this dissertation is to analyze and improve efficient adaptation strategies for pretrained ASR models on African-accented clinical speech, with emphasis on recognition performance, computational efficiency, and general-domain preservation.

## Research Questions

### RQ1: Error Analysis

What error patterns do state-of-the-art ASR models exhibit on African-accented clinical speech, and how do these patterns vary across clinical and general-domain speech?

### RQ2: PEFT vs Full Fine-Tuning

How do parameter-efficient fine-tuning methods compare with full fine-tuning for adapting Whisper-based ASR models to African-accented clinical speech in terms of recognition performance, computational efficiency, and trainable parameter cost?

### RQ3: Domain-Aware Adaptation

What domain-aware adaptation strategy can best balance specialization to African-accented clinical speech with preservation of general-domain ASR capability?

## Repository Structure

- `shared/`: shared utilities for data loading, normalization, metrics, and plotting
- `rq1_error_analysis/`: scripts, configs, and results for RQ1
- `rq2_peft_comparison/`: scripts, configs, and results for RQ2
- `rq3_domain_aware_peft/`: scripts, configs, and results for RQ3
- `tables/`: proposal-ready result tables
- `docs/`: experiment logs, data paths, weekly notes, and proposal mapping

## Current Deadlines

- Proposal submission: August 19, 2026
- Proposal defense: October 1, 2026