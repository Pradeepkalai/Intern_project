# Intern_project
#Day 1:
Text Normalization, Tokenization and Stopword Removal using NLTK
Overview:

This project demonstrates basic Natural Language Processing (NLP) preprocessing techniques using Python and NLTK.

The program performs:

*Text Normalization (Converts text to lowercase)

*Tokenization (Splits text into words)

*Stopword Removal (Removes common English words)

Technologies Used:
*Python 3.x

*NLTK (Natural Language Toolkit)

*Required Libraries

Install NLTK using:

pip install nltk

Download Required NLTK Resources

The following datasets are downloaded automatically when the program runs:

nltk.download('punkt')

nltk.download('punkt_tab')

nltk.download('stopwords')

How the Program Works:
Step 1: Input Text

User enters a paragraph.

Step 2: Text Normalization

Converts all characters to lowercase.

Example:

Hello World

becomes

hello world

Step 3: Tokenization

Splits text into individual words.

Example:

hello world

becomes

['hello', 'world']

Step 4: Stopword Removal

Removes common English words such as:

is, am, are, the, and, of, in

Resulting in meaningful words only.
