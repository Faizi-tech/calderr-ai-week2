# Day 2 – Structured Outputs with Pydantic & LangChain

## Overview

Day 2 focused on understanding **Structured Outputs** and **Pydantic v2**, which are essential for building reliable AI applications. The notebook demonstrates how to create validated data models, enforce constraints, apply custom validation, and prepare schemas that can be used with Large Language Models (LLMs) through LangChain.

---

## Objectives

- Understand the concept of Structured Outputs
- Learn the fundamentals of Pydantic v2
- Create data models using `BaseModel`
- Perform automatic data validation
- Apply field constraints using `Field()`
- Implement custom validation using `field_validator`
- Configure models with `model_config`
- Use field aliases
- Design reusable AI output schemas
- Prepare structured outputs for LangChain integration

---

## Topics Covered

- Structured Outputs
- Pydantic BaseModel
- Type Validation
- Automatic Type Conversion
- Validation Errors
- Default Values
- Exporting Models
- Field Constraints
- Custom Validators
- Model Configuration
- Field Aliases
- AI Output Schemas
- LangChain Preparation

---

## Practical Work Completed

- Created multiple Pydantic models.
- Validated different data types.
- Explored automatic type conversion.
- Handled validation errors.
- Applied field constraints.
- Implemented custom validators.
- Configured models using `model_config`.
- Used aliases for flexible field names.
- Built five reusable Pydantic models.
- Created a sample `JobPosting` schema for AI applications.
- Initialized the Groq LLM using LangChain.
- Prepared the project for structured output extraction.

---

## Technologies Used

- Python 3.13
- Jupyter Notebook
- Pydantic v2
- LangChain
- LangChain-Groq
- python-dotenv
- Groq API
- VS Code
- Git & GitHub

---

## Files

```
day2/
├── day2_structured_outputs.ipynb
└── README.md
```

---

## Learning Outcomes

After completing Day 2, I can:

- Create structured data models using Pydantic.
- Validate and sanitize input data automatically.
- Apply field constraints and custom validation rules.
- Configure model behaviour using `model_config`.
- Use aliases to improve compatibility with external APIs.
- Export models as dictionaries and JSON.
- Design schemas suitable for AI-generated structured outputs.
- Prepare LangChain applications for structured data extraction.

---

## Next Steps

The concepts learned in Day 2 will be applied in **Lab 2.1 – Structured Output Extractor**, where a LangChain application will extract structured information from unstructured job postings using a validated Pydantic schema.

---

## Author

**Faizan Ahmad**

BS Artificial Intelligence  
FAST National University of Computer and Emerging Sciences