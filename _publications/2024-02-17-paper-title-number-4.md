---
title: "Personalized AI-Driven Real-Time Models to Predict Stress-Induced Blood Pressure Spikes Using Wearable Devices: Proposal for a Prospective Cohort Study"
collection: publications
permalink: aliknd.github.io/publication/2024-02-17-paper-title-number-4
excerpt: 'The aim of this study is to leverage machine learning (ML) algorithms for real-time predictions of stress-induced BP spikes using consumer wearable devices such as Fitbit, providing actionable insights to both patients and clinicians to improve diagnostics and enable proactive health monitoring. This study also seeks to address the significant challenges in identifying specific deleterious behaviors associated with stress-induced hypertension through the development of personalized artificial intelligence models for individual patients, departing from the conventional approach of using generalized models.'
date: 2024-03-25
venue: 'JMIR'
paperurl: 'https://aliknd.github.io/files/paistress.pdf'
citation: 'Kargarandehkordi, A., Slade, C., & Washington, P. (2024). Personalized AI-Driven Real-Time Models to Predict Stress-Induced Blood Pressure Spikes Using Wearable Devices: Proposal for a Prospective Cohort Study. JMIR Research Protocols, 13(1), e55615.'
---

Background:
Referred to as the “silent killer,” elevated blood pressure (BP) often goes unnoticed due to the absence of apparent symptoms, resulting in cumulative harm over time. Chronic stress has been consistently linked to increased BP. Prior studies have found that elevated BP often arises due to a stressful lifestyle, although the effect of exact stressors varies drastically between individuals. The heterogeneous nature of both the stress and BP response to a multitude of lifestyle decisions can make it difficult if not impossible to pinpoint the most deleterious behaviors using the traditional mechanism of clinical interviews.

Objective:
The aim of this study is to leverage machine learning (ML) algorithms for real-time predictions of stress-induced BP spikes using consumer wearable devices such as Fitbit, providing actionable insights to both patients and clinicians to improve diagnostics and enable proactive health monitoring. This study also seeks to address the significant challenges in identifying specific deleterious behaviors associated with stress-induced hypertension through the development of personalized artificial intelligence models for individual patients, departing from the conventional approach of using generalized models.

Methods:
The study proposes the development of ML algorithms to analyze biosignals obtained from these wearable devices, aiming to make real-time predictions about BP spikes. Given the longitudinal nature of the data set comprising time-series data from wearables (eg, Fitbit) and corresponding time-stamped labels representing stress levels from Ecological Momentary Assessment reports, the adoption of self-supervised learning for pretraining the network and using transformer models for fine-tuning the model on a personalized prediction task is proposed. Transformer models, with their self-attention mechanisms, dynamically weigh the importance of different time steps, enabling the model to focus on relevant temporal features and dependencies, facilitating accurate prediction.

Results:
Supported as a pilot project from the Robert C Perry Fund of the Hawaii Community Foundation, the study team has developed the core study app, CardioMate. CardioMate not only reminds participants to initiate BP readings using an Omron HeartGuide wearable monitor but also prompts them multiple times a day to report stress levels. Additionally, it collects other useful information including medications, environmental conditions, and daily interactions. Through the app’s messaging system, efficient contact and interaction between users and study admins ensure smooth progress.

Conclusions:
Personalized ML when applied to biosignals offers the potential for real-time digital health interventions for chronic stress and its symptoms. The project’s clinical use for Hawaiians with stress-induced high BP combined with its methodological innovation of personalized artificial intelligence models highlights its significance in advancing health care interventions. Through iterative refinement and optimization, the aim is to develop a personalized deep-learning framework capable of accurately predicting stress-induced BP spikes, thereby promoting individual well-being and health outcomes.

International Registered Report Identifier (IRRID):
DERR1-10.2196/55615

JMIR Res Protoc 2024;13:e55615
