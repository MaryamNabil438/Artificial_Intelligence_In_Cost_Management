# Artificial_Intelligence_In_Cost_Management
CostAI: A Unified Multi-Technology AI System for Cost Management

Bachelor Thesis | The German University in Cairo
Author: Maryam Mohamed Nabil
Supervisor: Dr. Ayman Alserafi


This README file includes: Presentation, User Stories, Wireframe, System Architecture, Test Cases of the implemented prototype



## Project Overview

CostAI is a unified AI-powered cost management platform designed to serve five distinct business roles: CFO, Finance Manager, Cost Analyst, Cost Controller, and Department Manager, all within a single system.

The system integrates six AI technologies:
- Machine Learning — expense categorization, cost forecasting (Prophet, XGBoost)
- Anomaly Detection — dual model using Autoencoder and Isolation Forest
- NLP — intent classification and Named Entity Recognition for the Ask CostAI chatbot
- Computer Vision — 3-stage document scanning pipeline (ViT + LayoutLM + TrOCR)
- Generative AI — scenario narrative generation and AI cost-saving recommendations
- Scenario Simulation — Gradient Boosting with feature importance for cost projections

The prototype was designed using **Figma** and developed following the **Design Science Research Methodology (DSRM)** by Peffers et al.
Two prototype versions were produced and evaluated through expert interviews.

---

## System Design

All wireframes and UI designs were created in Figma.

> 🔗 **View interactive Figma prototype here:** https://www.figma.com/make/M6NV6aVgv67a2xxtoX73Ap/AI-Cost-Management-System--1---1-?t=Ght8wkQ7VIuNTCDq-1 

Exported screen designs are available in the folder, organized by role: CFO Dashboard, Finance Manager Dashboard, Cost Analyst Dashboard, Cost Controller Dashboard, and Department Manager Dashboard.

---

## Key Features

| Role | Key Capabilities |
|---|---|
| CFO | KPI overview, forecasting (30/60/90 days), scenario simulation, AI recommendations |
| Finance Manager | Expense submission with auto-categorization, anomaly alerts, document scanning |
| Cost Analyst | Anomaly investigation, trend analysis, visual analytics, report generation |
| Cost Controller | Contract management, variance analysis, budget tracking |
| Department Manager | Budget overview, spending breakdown, weekly AI narrative summary |

---

## AI Modules

- **Expense Categorization:** ML + NLP classification (XGBoost, Random Forest, text vectorization)
- **Anomaly Detection:** Autoencoder (deep learning) + Isolation Forest (unsupervised ML)
- **Cost Forecasting:** Prophet / ARIMA / LSTM — selectable per use case
- **Scenario Simulation:** Gradient Boosting with feature importance scores
- **Document Scanning:** ViT layout detection → LayoutLM region identification → TrOCR text extraction
- **Ask CostAI Assistant:** NLP intent classification + NER for plain-language queries

---

## How to Run

Since this is a design-based prototype developed in Figma, the primary deliverable is the interactive UI design rather than deployable code.

To explore the system: Open the Figma prototype link above. Navigate between role dashboards using the left sidebar. Refer to png uploaded files for exported screen-by-screen views and Main BPMN of the prototype. 
Or you can use the Full Implementation Code of CostAI folder uploaded here to run on VSC. 

## Evaluation

The prototype was evaluated through two structured expert interviews:
- **Expert 1:** AI Specialist
- **Expert 2:** Practicing Cost Controller

Feedback from Version 1 led to significant improvements in Version 2, including upgraded anomaly detection, an expanded NLP assistant, the addition of the Cost Controller dashboard, and a full document scanning pipeline.
