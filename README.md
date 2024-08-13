# Language-Translation

## Installation Instructions

1. Upgrade TensorFlow GPU to version 2.0:
    ```python
    !pip install --upgrade tensorflow-gpu==2.0
    ```

2. Install the required libraries:
    - NLTK:
        ```python
        !pip install nltk
        ```
    - Gensim:
        ```python
        !pip install gensim
        ```
    - SpaCy and Plotly:
        ```python
        !pip install spacy
        !pip install plotly
        ```

3. Download necessary NLTK packages:
    - Download `punkt` tokenizer models:
        ```python
        import nltk
        nltk.download('punkt')
        ```
    - Download stopwords:
        ```python
        nltk.download("stopwords")
        ```

4. Upgrade additional libraries:
    - Pillow:
        ```python
        !pip install --upgrade Pillow
        ```
    - WordCloud:
        ```python
        !pip install --upgrade wordcloud
        ```
