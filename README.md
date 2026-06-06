# NeuroScript — Z Formal Specification

## Overview

NeuroScript is an AI-powered handwriting analysis system designed for early neurological condition screening, specifically targeting ADHD and OCD detection through neuromotor handwriting features.

This repository contains the complete formal specification of the NeuroScript system using Z Notation and LaTeX.

The specification models:

* User management
* Handwriting sample processing
* Feature extraction
* LSTM-based classification
* SHAP/LIME explanation generation
* Archiving and administrative operations
* Error handling and robust schemas

---

## Project Objective

The goal of this project is to formally specify the behavior, constraints, and operational logic of an AI-based neurological handwriting analysis system using formal methods.

The system performs:

* Handwriting sample submission
* Neuromotor feature extraction
* Neurological prediction
* Explainable AI analysis
* Secure data handling

---

## Technologies & Concepts Used

* Z Notation
* LaTeX
* Formal Methods
* Artificial Intelligence
* LSTM-Based Prediction Models
* SHAP / LIME Explainability
* Software Specification & Verification

---

## Repository Structure

```text
.
├── NeuroScript_Z_Specification.tex
├── NeuroScript_Z_Specification.pdf
└── README.md
```

---

## Formal Specification Includes

### Basic Type Definitions

* USER
* SAMPLEID
* FEATUREVECTOR
* EXPLANATION

### Free-Type Enumerations

* ROLE
* CONDITION
* SAMPLESTATUS
* REPORT

### Core Schemas

* State-space schema
* Initial-state schema
* Operational schemas
* Error schemas
* Robust combined operations

### Main Operations

* Register User
* Login User
* Upload Handwriting Sample
* Extract Features
* Classify Sample
* Generate Explanation
* Retrieve Predictions
* Archive Samples
* Delete User Accounts

---

## Key Features

* Formal verification-oriented design
* Robust error handling using REPORT free types
* AI-integrated specification modeling
* Explainable AI workflow representation
* Clean schema decomposition
* Mathematical state invariants

---

## How to Compile

Compile the LaTeX source using:

```bash
pdflatex NeuroScript_Z_Specification.tex
```

Or compile using Overleaf.

---

## License

This project is licensed under the MIT License.

---

## Preview

The PDF version of the specification is included in this repository for direct viewing.
