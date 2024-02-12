# Arabic Text Classification


![Arabic Text Classification(1)](https://github.com/Aml-Hassan-Abd-El-hamid/Text-Classification-Using-BERT/assets/66205928/f8e3535b-8b9b-441c-93e6-a389766326d9)

This project was inspired by the Large Language Models: Text Classification for NLP using BERT course from LinkedIn Learning, I wanted to apply what I learned in that course in a small project, and because I wanted to go the extra mile and force myself to dig deeper, I chose to work with Arabic text - my mother tongue is Arabic - instead of the English text dataset that was used in the course.

### The Dataset

I started this project of course by hunting my dataset, there aren't many public Arabic text datasets compared to English ones, but I eventually found myself this nice [dataset](https://data.mendeley.com/datasets/v524p5dhpj/2), there were no much info provided regarding that dataset but that what was mentioned in the dataset description:
```
The dataset is a collection of Arabic texts, which covers modern Arabic language used in newspapers articles.
The text contains alphabetic, numeric and symbolic words. The existence of numeric and symbolic words in this
dataset could tell the efficiency and robustness of many Arabic text classification and indexing documents.

The dataset consists of 111,728 documents (cf. Table 1) and 319,254,124 words (cf. Table 2) structured in text files,
and collected from 3 Arabic online newspapers:  Assabah [9], Hespress [10] and Akhbarona [11] using semi-automatic web crawling process.
The documents in the dataset are categorized into 5 classes: sport, politic, culture, economy and diverse. The number of documents
and words for each class varies from one class to another (cf. Tables 1-2)
```


I started by conducting a simple EDA to figure out more about this dataset, and here's the most important information that I got: 



#### Dataset citation
mohamed, BINIZ (2018), “DataSet for Arabic Classification”, Mendeley Data, V2, doi: 10.17632/v524p5dhpj.2
