# Prompt-driven-antonym-finder

This Python script demonstrates how to find antonyms of words using NLTK's WordNet and generate prompts using Few-Shot Prompt Templates.

## Requirements

- Python 3.x
- nltk (Natural Language Toolkit)

## Installation

1. Clone the repository or download the script.
2. Install NLTK and necessary data files:
   ```bash
   pip install nltk
   python -m nltk.downloader wordnet
   ```

## How It Works

This script allows you to input a word and find its antonym using NLTK's WordNet. It then generates a formatted prompt using Few-Shot Prompt Templates.

### Components

- **find_antonym(word)**: Uses NLTK's WordNet to find the antonym of a given word.
- **get_antonym_prompt()**: Takes user input, finds the antonym using `find_antonym`, and formats a prompt using `FewShotPromptTemplate`.
- **FewShotPromptTemplate**: A template class that formats prompts based on predefined examples.

### Usage

1. Run the script.
2. Enter a word when prompted.
3. The script will find and display the antonym of the word, or indicate if no antonym was found.

### Example

If you input "happy", it will find "sad" as the antonym.

## Files

- **antonym_finder.py**: Main script file.
- **README.md**: This file, explaining the script and its usage.


