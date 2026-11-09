
# AI Response Evaluation & Testing System

A beginner-friendly Python project designed to evaluate chatbot responses and perform automated AI response testing using Pytest and Promptfoo.

## Project Overview

This project demonstrates a basic automated testing framework that checks chatbot responses against predefined evaluation rules.

It generates sample responses, evaluates their quality, detects basic prompt injection attempts, and saves evaluation results in a JSON report.

## Technologies Used

- Python
- Pytest
- Promptfoo
- JSON
- YAML

## Features

1. Automated chatbot response generation.
2. Expected keyword validation.
3. Basic response relevance checking.
4. Minimum response length validation.
5. Basic prompt injection detection.
6. Automated testing using Pytest.
7. Prompt evaluation using Promptfoo.
8. JSON-based evaluation reports.

## Project Structure

```text
AI_Response_Evaluation_System/
│
├── tests/
│   └── test_evaluator.py
│
├── evaluator.py
├── provider.py
├── main.py
├── promptfooconfig.yaml
├── requirements.txt
├── README.md
└── report.json
```

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd AI_Response_Evaluation_System
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Project

Execute the main application:

```bash
python main.py
```

## Run Automated Tests

Using Pytest:

```bash
python -m pytest -v
```

Using Promptfoo:

```bash
npx promptfoo@latest eval
```

## Evaluation Report

The application generates a JSON report containing:

- Total test cases
- Passed test cases
- Failed test cases
- Individual AI responses
- Evaluation results

## Project Limitations

- Uses predefined mock responses instead of a live AI model.
- Uses basic rule-based evaluation.
- Prompt injection detection covers only predefined phrases.
- Does not perform advanced semantic accuracy or hallucination evaluation.

## Future Improvements

- Integrate a real LLM API.
- Add semantic response evaluation.
- Implement hallucination detection.
- Expand prompt injection test datasets.
- Add response latency and cost monitoring.

## Author

Developed as a beginner-level AI Quality Assurance and automated testing project.
