# 🔎 Named Entity Recognition

## 📌 Objective

The objective of this project is to identify and classify important named entities from text using Natural Language Processing (NLP).

The system can identify entities such as:

- PERSON
- ORGANIZATION
- LOCATION
- DATE
- MONEY
- PRODUCT
- EVENT

## 🛠️ Technologies Used

- Python
- spaCy
- Pandas
- Gradio
- Google Colab

## 🧠 Methodology

The project uses spaCy's pretrained `en_core_web_sm` model for Named Entity Recognition.

### Workflow

User Text
↓
spaCy NLP Model
↓
Named Entity Recognition
↓
Entity Classification
↓
Display Results

## 🔍 Example

Input:

"Apple announced a new product in California on September 10, 2026."

Output:

| Entity | Label |
|---|---|
| Apple | ORG |
| California | GPE |
| September 10, 2026 | DATE |

## ✨ Features

- Detects named entities from text
- Identifies entity categories
- Displays entity descriptions
- Supports multiple sentences
- Interactive Gradio interface
- Easy to run in Google Colab

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Download the spaCy English model.
4. Run the notebook cells.
5. Enter text into the Gradio interface.
6. Click **Extract Entities**.

## 📦 Installation

```bash
pip install spacy pandas gradio
python -m spacy download en_core_web_sm
