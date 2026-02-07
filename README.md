# Sawab: Arabic Spelling Correction AI System

## Overview
Sawab is an AI-powered educational system designed to detect and correct common Arabic spelling errors while promoting linguistic understanding.
Unlike traditional spell-checkers that only provide corrections, Sawab explains the linguistic rule behind each correction, transforming error correction into an interactive learning experience.

This project was developed during a hackathon, focusing on building a practical, intelligent solution for Arabic language learners and students.

Sawab targets common spelling challenges in Arabic, particularly:
- Hamza-related errors
- Confusion between Ta Marbuta (ة) and Ha (ه)
- Correct sentences with no spelling errors

## Hackathon Context
This project was developed as part of a hackathon under the Arabic Natural Language Processing and Education Technology track.
The goal was to design an intelligent system that combines machine learning with educational feedback to address real-world language learning challenges.

## Features
- Fine-tuned Arabic language model based on CAMeLBERT
- Automatic classification of Arabic spelling error types:
  - Hamza errors
  - Ta Marbuta / Ha errors
  - No error
- Rule-based correction modules for each error category
- Clear educational explanations for applied linguistic rules
- Supports Modern Standard Arabic and Classical Arabic
- Designed for scalability and real-world educational use

## Methodology
1. User inputs an Arabic sentence
2. Sentence is classified using a fine-tuned CAMeLBERT model
3. Based on the predicted error type, the sentence is routed to the appropriate correction module
4. The system applies the correction
5. A concise educational explanation is generated and presented to the user

This hybrid approach combines machine learning with rule-based linguistic knowledge.

## Technologies Used
- Python
- Jupyter Notebook
- CAMeLBERT (fine-tuned)
- Natural Language Processing (NLP)
- Machine Learning
- CSV-based labeled dataset

## Project Structure
sawab-arabic-spelling-correction-ai/
├── notebooks/
│   └── sawab_project.ipynb
├── data/
│   └── sawab_dataset.csv
├── docs/
│   └── Sawab-poster.pdf
└── README.md

## Results
The fine-tuned CAMeLBERT model demonstrated strong performance in classifying Arabic spelling error types across the targeted categories.
The system successfully detected and corrected common spelling errors while providing clear educational explanations, highlighting the effectiveness of task-specific fine-tuning for Arabic NLP tasks.

## Educational Impact
Sawab bridges the gap between automated correction and language learning by:
- Encouraging understanding of Arabic spelling rules
- Supporting students and language learners
- Enhancing the quality of Arabic digital content

## Future Work
- Support additional Arabic spelling and grammatical error types (e.g., Alif Maqsura, diacritics)
- Expand and diversify the training dataset
- Develop a web or mobile-based user interface
- Introduce personalized feedback based on user proficiency

## Notes
- This project was developed for a hackathon and educational purposes
- Personal data has been removed for public release
- The dataset can be replaced or extended for further research

## License
This project is intended for educational and research purposes only.
