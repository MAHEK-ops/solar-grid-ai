# Solar Grid AI — Intelligent Solar Energy Forecasting & Grid Optimization

An AI-driven system that forecasts solar energy generation and provides intelligent grid optimization recommendations using an agentic AI assistant.

## Project Overview

This project has two major components:

1. **Solar Energy Forecasting Engine** — ML models trained on hourly solar plant data
2. **Agentic AI Assistant** — LangGraph-based agent that analyzes forecasts and generates grid optimization strategies

## Project Structure

```
solar-grid-ai/
├── data/
│   ├── raw/              # Original dataset
│   └── processed/        # Cleaned & feature-engineered data
├── notebooks/            # EDA and experimentation notebooks
├── src/
│   ├── forecasting/      # ML model training & prediction
│   ├── agent/            # LangGraph AI agent
│   └── ui/               # Streamlit web interface
├── models/               # Saved trained models
├── reports/              # Generated forecast reports
└── docs/                 # Project documentation
```

## Setup

```bash
# Clone the repo
git clone 
cd solar-grid-ai

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Tech Stack

- **ML**: scikit-learn, XGBoost, statsmodels
- **Agent**: LangChain, LangGraph
- **UI**: Streamlit
- **Hosting**: Hugging Face Spaces / Streamlit Cloud
