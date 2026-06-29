---
title: "Project" # in any language you want
layout: "project" # is necessary
language: en
url: "/projects"
summary: Projects

comments: false
---

Hello Everyone, these are few of the many projects I have built and developed.

## PRISM — Precision Research and Information Systems for bioMedicine
A unified AI-augmented knowledge aggregation platform for the life sciences, built at Northeastern's Institute for Experiential AI. PRISM integrates Neo4j knowledge graphs, FastAPI backends, and multi-agent RAG systems to enable cross-domain scientific reasoning. The platform uses distributed AI agent swarms for autonomous graph construction, achieving 200x faster document processing than baseline Neo4j ingestion, and integrates with INDRA to deliver evidence-grounded biomedical causal insights at 5x lower cost than commercial AI platforms — accelerating drug discovery workflows.

## eGoT — Enhanced Graph-of-Thoughts
A novel multi-hop GraphRAG algorithm that combines adaptive graph traversal with LLM-driven reasoning. eGoT improves retrieval precision by 44% and faithfulness by 27% over prior SOTA on MultiHopRAG and HotPotQA, and achieves 98.8% win rates against competing GraphRAG methods including KAG. The Cypher query generation and knowledge graph construction pipelines leverage GPT-4, DeepSeek-V3, and modern embedding systems, processing biomedical literature and climate science data for cross-domain knowledge retrieval. Paper accepted at ISMB 2026.

## GeoSAFE — Geospatial AI Safety Assurance Framework
A safety assurance framework for geospatial AI, introducing a taxonomy of six critical hazard categories and addressing domain-specific safety concerns. Curated a dataset of 12,078 LLM-human interaction prompts and responses annotated for safety evaluation, applying data-centric AI principles to remove bias and improve fairness. Fine-tuned LlamaGuard and NeMo Guardrails to achieve a 97% F1 score, significantly reducing false-safe rates in geospatial AI prompts. Paper accepted at AACL-IJCNLP 2025.

## BRAHMA — Multi-Agent System for Automated Hypothesis Generation
A multi-agent system for automated scientific hypothesis generation with dual validation layers, co-designed as part of the PRISM platform at Northeastern's Institute for Experiential AI. BRAHMA performs co-occurrence analysis, claim verification, and global literature cross-referencing through a Neo4j-backed knowledge graph at scale, enabling autonomous reasoning across biomedical and climate science corpora.

## Idea11y — Accessible Collaborative Ideation for Low-Vision Users
An AI-powered Miro plugin that uses unsupervised ML clustering algorithms and applies HCI and Gestalt principles to enhance accessibility for low-vision users in digital collaboration spaces. Custom ML models analyze and restructure visual information in real-time, transforming complex ideation workspaces into accessible, navigable interfaces. The project led an interdisciplinary team to first-place victory in the Papers2Products hackathon at Northeastern University. Paper accepted at CHI 2026.

## Realtime Person Tracking and Re-Identification in Embodied Learning Environment
Engineered a high-performance person re-identification (Re-ID) system using a custom dataset and a deep learning pipeline in PyTorch, designed for real-time tracking in closed-room classroom settings. Achieved 92% mAP by fine-tuning TriNet and OSNet pre-trained models and applying ensemble learning. Integrated YOLOv8 with DeepSORT for real-time multi-object tracking, utilizing Kalman and Particle Filters for precise motion prediction, trajectory estimation, and minimized identity switches. Built as part of the NSF AI Engage Institute project at Vanderbilt's Institute for Software Integrated Systems.

## Affect Aware Tutoring System in E-Learning Systems (Pekanu E-Tutor)
Worked on a novel idea in the field of education technology, named "Affect Aware Tutoring System Using Video Bots". Built a learning management system that collects the click-stream log data of the student, simultaneously captures video and then predicts the user's affect state for real-time feedback. Developed an optimized transformer-based deep learning model using Vision Transformers, trained on the DAiSEE dataset for approximately 300 hours. Scaled the system at IIT Bombay to support concurrent usage by over 10,000 users. Paper documented and in submission at IEEE Transactions on Learning Technologies.

## Protein Fold Recognition
Implemented advanced NLP techniques to improve protein fold recognition in challenging low-similarity datasets (DD, EDD, TG, SCOPe) with diverse amino acid sequences and folds. Extracted features using evolutionary PSSM and HMM profiles, concatenated with global Convolutional and Skip Bi-gram features. Applied BERT and ESM (by Meta) transformer-based models for classification, achieving over 93% accuracy across all datasets — surpassing the previous 85% baseline. Paper under review in IEEE Journal of Biomedical and Health Informatics.

## PEcAn SDA and Forecasting Dashboard
This project is primarily focused on creating an interactive display of the carbon cycle forecast and data assimilation system of PEcAn. The main goal is to revive the site-specific R Shiny Forecasting and SDA dashboard that is no longer operational and broaden its scope to cover a larger number of sites. Additionally, the plan is to construct a new comprehensive dashboard that combines both SDA and Forecasting graphs. Moreover, the proposal also aims to establish an automated notification email system for the visualizations.

More information can be found [here](https://koolgax99.github.io/posts/gsoc-2023-final-report/)

## Extending APIs / Distributed File Sharing for PEcAn Project
The project aims at improving and extending the current PEcAn REST APIs by making them more robust and dynamic from the user's perspective. The security of the APIs was also improved by introducing an API KEY management system, rate limiting, and input validation.

More information can be found [here](https://koolgax99.github.io/posts/gsoc-2022-final-report/)

## Camp+

![Camp+](/img/camp+.png)

The application Camp+, built in Flutter and Node.js, manages deliveries, visitors to the campus, helps residents of the hostel in viewing and calling other residents of different hostels, allows booking housekeeping facilities, and solves several other essential needs relevant to residential campuses — including library booking, notice board management, cafeteria slot management, event booking management, room booking management, laundromat slot booking, and a canteen delivery system.
I led the team that built it as Founder and CEO of Varopro Private Limited, where we served a user base exceeding 800 individuals across multiple campuses and received grants and funding of more than $13,000. The startup was incubated by New Gen IEDC IIIT Allahabad, Government of India, under the Startup India initiative. I engineered the application's multi-tenant backend using AWS Lambda, DynamoDB, S3, SES, API Gateway, and the MEN (MongoDB, Express, Node) stack. For more information please check out the [Camp+](https://camplus.network/) website.
