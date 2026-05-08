# LLM-Software-Requirements

# LLM Requirements Quality Assurance

This repository contains the code and results for a comparative 
evaluation of GPT-4o-mini and Claude for software requirements 
quality assurance based on ISO 29148.

## Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- OpenAI API key
- Anthropic API key

## How to Run

1. Open `LLM_Requirements_QA.ipynb` in Google Colab
2. Click **Runtime > Run all**
3. When prompted, add your API keys in Colab Secrets:
   - `OPENAI_API_KEY` — your OpenAI API key
   - `ANTHROPIC_API_KEY` — your Anthropic API key

## Install Dependencies

Run this in the first cell:

pip install openai anthropic scikit-learn openpyxl

## What the Code Does

- Evaluates 15 software requirements against ISO 29148 
  quality characteristics
- Tests two models: GPT-4o-mini and Claude
- Tests two prompting strategies: basic and few-shot
- Calculates accuracy, precision, recall, and F1 score
- Generates bar charts and exports results to Excel

## Results

- Experiment 1: GPT-4o-mini basic achieved the highest 
  accuracy at 0.933
- Experiment 2: Claude few-shot achieved a perfect score 
  of 1.0 after improved prompt design
- All models achieved perfect recall of 1.0 in both 
  experiments
