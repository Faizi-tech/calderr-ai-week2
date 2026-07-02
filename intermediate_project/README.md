# Intermediate Project – Smart Form Filler

## Overview

This project implements an AI-powered Smart Form Filler using LangChain, Groq, and Pydantic.

The application extracts structured job application information from natural language, validates the extracted data, and generates clarification questions whenever required information is missing.

---

## Features

- Natural language understanding
- Structured output using Pydantic
- Automatic field extraction
- Validation of required fields
- Clarification for incomplete inputs
- Multiple test cases

---

## Technologies

- Python
- LangChain
- Groq
- Pydantic
- Jupyter Notebook

---

## Project Structure

```
intermediate_project/
│
├── smart_form_filler.ipynb
├── README.md
├── requirements.txt
├── test_cases.json
├── validation_report.md
└── sample_inputs/
```

---

## Workflow

```
User Input
      │
      ▼
Large Language Model
      │
      ▼
Structured Extraction
      │
      ▼
Validation
      │
      ▼
Missing Fields?
      │
      ├── Yes → Clarification Questions
      │
      ▼
Validated Form
```

---

## Key Learning Outcomes

- Prompt engineering for structured extraction
- Pydantic schema validation
- Structured outputs with LangChain
- Validation workflows
- AI-assisted form automation

---

## Author

**Faizan Ahmad**

BS Artificial Intelligence

FAST National University of Computer and Emerging Sciences