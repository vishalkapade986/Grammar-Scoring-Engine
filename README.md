# Grammar Scoring Engine 🎙️📝

[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/competitions/shl-intern-hiring-assessment)

An end-to-end system for evaluating grammar quality in spoken English using acoustic features and NLP analysis.
## Overview
This project aims to develop a Grammar Scoring Engine that analyzes audio recordings to predict grammar quality scores (0-5) based on both acoustic features and transcribed text. The solution leverages audio processing, NLP techniques, and machine learning to evaluate spoken grammar proficiency.

![Workflow Diagram](https://via.placeholder.com/800x400.png?text=Workflow+Diagram)

## Features ✨

- **Multi-modal Analysis**
  - Acoustic features (pitch, MFCCs, speech ratio)
  - Text features (grammar errors, readability scores)
- **Advanced NLP**
  - Whisper ASR for speech-to-text
  - spaCy POS tagging
  - LanguageTool grammar checking
- **ML Pipeline**
  - XGBoost regression model
  - Feature engineering pipeline
  - Cross-validation strategy

## Installation ⚙️

```bash
# Clone repository
git clone https://github.com/vishalkapade986/Grammer-Scoring-Engine.git
cd Grammar-Scoring-Engine

# Install dependencies
pip install -r requirements.txt

# Download spaCy model
python -m spacy download en_core_web_sm


