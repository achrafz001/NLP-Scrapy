# NLP-Scrapy
Tutoried project : Harshit Tyagi

**Goals of the Project**

The goal of this project is to learn and apply Named Entity Recognition to extract important entities (publicly traded companies in our example) and then link each entity with some information using a knowledge base (Nifty500 companies list).

We’ll get the textual data from RSS feeds on the internet and extract the names of buzzing stocks. We'll then pull their market price data to test the authenticity of the news before taking any position in those stocks.

**Steps to start the project**

1.  pip install -r requirements.txt
2.  python -m spacy download en_core_web_sm
3.  streamlit run app.py

