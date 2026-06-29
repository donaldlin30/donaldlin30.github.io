---
layout: page
title: Reflect — EEG-Powered Meditation App
description: Real-time neurofeedback from wearable EEG
img: assets/img/ECG_reflect.jpeg
importance: 2
category: graduate
related_publications: false
---

Reflect is a full-stack, real-time EEG application I built with a team of 4. It integrates a Muse headset over Bluetooth via the Muse-LSL / Lab Streaming Layer stack, with sliding-window feature extraction and per-second inference driving live neurofeedback.

I benchmarked XGBoost, LightGBM, random forest, and SVM on 2,479 samples (988 features), and deployed an XGBoost classifier (0.98 F1, 0.99 AUROC) with a ~1-minute per-user fine-tuning step to handle inter-user variability. I also developed the React/TypeScript dashboard (Vite, Recharts) for device setup, signal-quality verification, calibration, and post-session time-series visualization of meditation states.

The project was funded by a University of Michigan Library mini-grant and featured in the <a href="https://blogs.lib.umich.edu/student-stories/building-reflect-eeg-powered-mindfulness-app" target="_blank">U-M Library Student Stories</a> spotlight.
