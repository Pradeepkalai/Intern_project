# Intern_project
Day 1: Text Normalization, Tokenization, and Stopword Removal using NLTK

Overview:

This project demonstrates fundamental *Natural Language Processing (NLP)* preprocessing techniques using Python and the Natural Language Toolkit (NLTK).

The program focuses on three core operations:

* Text Normalization: Converts text to lowercase to maintain uniformity.
* 
* Tokenization: Splits text strings into individual words or tokens.
* 
* Stopword Removal: Filters out common English words to retain only the meaningful vocabulary.

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
