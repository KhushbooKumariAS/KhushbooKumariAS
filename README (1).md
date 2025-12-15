# ATS Resume Evaluation Tool

## Overview
This project is an ATS (Applicant Tracking System) Resume Evaluation Tool designed to analyze resumes and assess their compatibility with job descriptions. It helps automate resume screening by extracting relevant skills and keywords using Natural Language Processing (NLP).

## Problem Statement
Recruiters receive a large number of resumes, making manual screening time-consuming and inefficient. ATS systems are used to filter resumes, but many candidates are unaware of how their resumes are evaluated. This project aims to analyze resumes and provide insights into ATS compatibility.

## Features
- Resume text extraction from PDF documents
- Keyword and skill extraction using NLP techniques
- Resume and job description matching
- ATS compatibility scoring
- Storage and retrieval of resume data using SQL

## Methodology
1. Extracted text from resumes using Python libraries.
2. Cleaned and preprocessed textual data.
3. Applied NLP techniques to identify skills and keywords.
4. Matched resume content with job descriptions to compute an ATS score.
5. Stored processed data in a SQL database for efficient querying.

## Tools & Technologies
- Python
- Natural Language Processing (NLP)
- NLTK / spaCy
- SQL
- Scikit-learn
- PyPDF2

## Outcome
The tool successfully evaluates resumes by extracting relevant information and providing an ATS compatibility score, helping improve recruiter screening efficiency and candidate awareness.

## Conclusion
This project demonstrates how NLP and data analysis techniques can be applied to build an automated resume evaluation system aligned with real-world ATS workflows.
