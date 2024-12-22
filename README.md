# Sinhala Spelling and Grammar Checker

A Python-based tool for detecting and correcting spelling and grammar errors in Sinhala text. This project utilizes advanced algorithms, including phonetic matching, fuzzy string matching, and stemming techniques, to identify and correct errors in Sinhala writing.

## Features
- **Spell Checking**: Detects and suggests corrections for misspelled Sinhala words.
- **Grammar Checking**: Identifies grammatical mistakes and provides suggestions.
- **Advanced Phonetic Matching**: Uses phonetic similarity to suggest corrections for words with similar sounds.
- **Fuzzy Matching**: Applies fuzzy matching techniques for string similarity.
- **Stopword Removal**: Removes common stopwords to improve accuracy.
- **Custom Dictionary**: Allows customization with a dictionary file.

## Requirements

Before running the application, make sure you have the following Python libraries installed:

- `pandas` for data handling.
- `numpy` for numerical operations.
- `fuzzywuzzy` for fuzzy string matching.
- `openpyxl` for reading Excel files (if using Excel dictionary).
- `re` for regular expressions.

You can install these libraries using `pip`:

```bash
pip install pandas numpy fuzzywuzzy openpyxl
