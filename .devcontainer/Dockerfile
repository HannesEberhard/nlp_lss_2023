
FROM python:3.8

RUN apt-get update && apt-get install -y graphviz

RUN pip install \
    pandas \
    tqdm \
    gensim \
    beautifulsoup4 \
    googletrans \
    matplotlib \
    spacytextblob \
    lxml \
    transformers[torch] \
    unidecode \
    seaborn \
    sklearn \
    wordcloud \
    fightin-words \
    eli5 \
    flair \
    tensorflow \
    keras \
    sentencepiece \
    scikit-learn-extra \
    pyldavis \
    hdbscan \
    pydot \
    jupyterlab \
    nltk

RUN python -m spacy download en_core_web_sm && \
    python -c "import nltk; nltk.download('wordnet');" && \
    python -c "import nltk; nltk.download('stopwords');" && \
    python -c "import nltk; nltk.download('vader_lexicon');"
