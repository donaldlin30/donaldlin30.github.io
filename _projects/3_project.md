---
layout: page
title: Blood Glucose Forecasting from CGM Data
description: Deep learning for continuous glucose monitoring @ Michigan Medicine (journal manuscript in submission)
img: assets/img/CGM.jpg
importance: 1
category: graduate
related_publications: false
---

As a Graduate Research Assistant in machine learning for healthcare, I build LSTM-based deep learning models for blood glucose forecasting on large-scale continuous glucose monitoring (CGM) data from Michigan Medicine, improving RMSE and clinical accuracy metrics over baselines.

A central finding is that a single global model trained on population data can outperform individualized models that require 40+ days of per-patient data, drastically reducing the data needed for deployment. I validated this cross-cohort generalization on the OhioT1DM benchmark, enabling scalable personalized prediction via population-level pretraining.

I also deployed and served small-scale LLMs locally (Hugging Face, vLLM) to prototype an LLM-based clinical reasoning system over CGM time-series data. This feasibility prototype helped secure the Laude Institute Moonshot Grant (Frontline Healthcare).

A journal manuscript based on this work is currently in submission.
