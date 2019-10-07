# python-crf-NER
Train a CRF classifier for named entity recognition

---
In an attempt to increase the speed of tagging countries in a corpus, a country CRF classifier was trained and applied in place of the conventional string match-and-replace approach

Modelling approach was inspired by http://www.albertauyeung.com/post/python-sequence-labelling-with-crf/

Training data was collected by scraping news websites, with country as the input.
Code can be found [here](https://github.com/bohaoo/news-sites-scraper)