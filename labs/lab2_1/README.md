# Lab 2.1 – Structured Output Extractor

## Overview

This lab demonstrates how to build a **Structured Output Extractor** using **LangChain**, **Groq**, and **Pydantic v2**. The application accepts an unstructured job posting and extracts important information into a validated Pydantic model, making the data easy to process programmatically.

---

## Objective

The objective of this lab is to convert unstructured job advertisements into structured data using a predefined schema.

The extracted information includes:

- Job Title
- Company Name
- Salary Range
- Required Skills
- Location
- Remote Status

---

## Technologies Used

- Python 3.13
- Jupyter Notebook
- LangChain
- LangChain-Groq
- Pydantic v2
- python-dotenv
- Pandas
- Groq API
- VS Code
- Git & GitHub

---

## Project Workflow

```
Unstructured Job Posting
          │
          ▼
      LangChain
          │
          ▼
      Groq LLM
          │
          ▼
Structured Output
          │
          ▼
 Pydantic Validation
          │
          ▼
 Validated Python Object
          │
          ▼
 Dictionary / JSON / DataFrame
```

---

## Features

- Load API key securely using `.env`
- Connect to Groq LLM through LangChain
- Create a structured schema using Pydantic
- Extract structured information from free-text job postings
- Validate AI-generated responses automatically
- Convert structured data into Python dictionaries and JSON
- Display extracted information in a Pandas DataFrame
- Handle unexpected errors using exception handling

---

## Files

```
lab2_1/
├── lab2_1_structured_output_extractor.ipynb
└── README.md
```

---

## Sample Extracted Fields

The application extracts the following information from job postings:

- Job Title
- Company
- Salary Range
- Required Skills
- Location
- Remote Status

---

## Learning Outcomes

After completing this lab, I can:

- Design structured schemas using Pydantic.
- Generate structured outputs from LLMs using LangChain.
- Validate AI-generated responses automatically.
- Convert structured outputs into Python objects, dictionaries, and JSON.
- Display extracted information in a tabular format using Pandas.
- Build AI pipelines that transform unstructured text into reliable structured data.

---

## Future Improvements

Possible enhancements include:

- Extract additional fields such as experience level, education requirements, and employment type.
- Process multiple job postings from PDF or Word documents.
- Export structured data to CSV or a database.
- Build a web interface using Streamlit or FastAPI.
- Integrate support for multiple LLM providers.

---

## Conclusion

This lab demonstrates how Large Language Models can be integrated with LangChain and Pydantic to reliably transform unstructured text into validated structured data. Such pipelines are widely used in AI-powered automation systems, recruitment platforms, document processing, and information extraction applications.

---

## Author

**Faizan Ahmad**

BS Artificial Intelligence  
FAST National University of Computer and Emerging Sciences