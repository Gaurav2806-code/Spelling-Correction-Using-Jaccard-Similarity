# Spelling-Correction-Using-Jaccard-Similarity

A simple Python project that implements a basic **spell checker** using the **Jaccard Similarity** algorithm and **character n-grams (bigrams)**. The project compares a misspelled word with a predefined dictionary and returns the closest matching word based on similarity score.

## 📌 Features

- Generate character n-grams (default: bigrams)
- Calculate Jaccard Similarity between words
- Find the most similar word from a dictionary
- Preprocess input by:
  - Converting text to lowercase
  - Removing special characters
- Display the best matching word along with its similarity score

## 🛠️ Technologies Used

- Python
- Jupyter Notebook

## 📂 Project Workflow

1. Create a dictionary of correctly spelled words.
2. Convert each word into character n-grams.
3. Compute Jaccard Similarity between the input word and each dictionary word.
4. Select the word with the highest similarity score.
5. Return the corrected spelling.

## 📊 Example

**Input:**

```text
camputer
meimory
divice
hardbare
mause
```

**Output:**

```text
camputer → computer
meimory → memory
divice → device
hardbare → hardware
mause → mouse
```

## 📚 Concepts Used

- Jaccard Similarity
- Character N-Grams
- Set Operations
- String Preprocessing
- Basic Natural Language Processing (NLP)


## 🎯 Learning Outcome

This project demonstrates how similarity metrics can be used to perform basic spelling correction without using machine learning models. It provides a practical introduction to text preprocessing, set theory, and NLP fundamentals.

---
⭐ If you found this project useful, consider giving it a star!
