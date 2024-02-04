# Spam Email Detection

## Introduction

This is a college project designed for detecting spam emails using machine learning. The project utilizes various Python modules and technologies to achieve its goal.

## Modules Used

### Streamlit

[Streamlit](https://www.streamlit.io/) is an open-source Python library that simplifies the process of creating and sharing custom web apps for machine learning and data science. It provides an interactive and user-friendly interface for users to interact with machine learning models.

### Pickle

[Pickle](https://docs.python.org/3/library/pickle.html) is a Python module used for serializing and deserializing Python objects. It plays a crucial role in storing object structures in files or databases, maintaining program state across sessions, or transporting data over the network.

### String

The [string module](https://docs.python.org/3/library/string.html) in Python provides a single utility function - `capwords(s, sep=None)`. This function splits the specified string into words using `str.split()`, then capitalizes each word using `str`.

### NLTK (Natural Language Toolkit)

[NLTK](https://www.nltk.org/) is a powerful Python package for Natural Language Processing (NLP). In this project, NLTK is employed for text processing and analysis. It assists in handling unstructured data containing human-readable text, which is common in email content.

## How to Run

To execute the program, follow these steps:

1. Ensure you have Python installed on your machine.
2. Open a terminal.
3. Run the command: `streamlit run app.py`

This command will launch the application and make it accessible through a web browser.

## Project Structure

- `app.py`: Main Python script containing the Streamlit application code.
- `model.pkl`: Pickle file storing the trained machine learning model.
- `requirements.txt`: File specifying the required Python dependencies.

Feel free to explore and modify the project according to your needs. If you encounter any issues or have questions, don't hesitate to reach out.

Happy spam email detection! 🚫📧