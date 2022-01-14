# Wikipedia_NLP_Application
This is a interactive app I created with ploty dash that allows users to explore all of Wikipedia pages via API and will return details on Named Entity Recognition (NER) and TF-IDF scores for specified pages. The application is fully written in python.

Features:
- A section that returns 10 suggested pages to explore on your specified topic.
- A section for more insight into a specific page, insights include:
    - Return of the URL of the page being examined.
    - Number of entities found on the page along with a barplot to demonstrate the entity categories.
    - The top 10 most used entities.
    - The top 10 TF-IDF scores found in the page along with the word.

Definitions:

NLP - Natural Laguage Processing - refers to the branch of computer science—and more specifically, the branch of artificial intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can.

NER - Named Entity Recognition - is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc

TF-IDF - short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.




![dash app demo](python-dash-demo.gif)
