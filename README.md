# LEAR
The implementation our EMNLP 2021 paper ["Enhanced Language Representation with Label Knowledge for Span Extraction"](https://arxiv.org/pdf/2111.00884.pdf).

See below for an overview of the model architecture:

<center><img width="80%" src="https://cdn.jsdelivr.net/gh/Akeepers/blog-resource/picture/20211107211214.png"></center>

## Requestments

* python 3.6
* pytorch 1.8
* transformers 3.9.2
* prefetch_generator
* tokenizers

## Data

| Task            | Url                                                  | Rreprocess scripts |
|-----------------|------------------------------------------------------|--------------------|
| NER             | [mrc-for-flat-nested-ner](https://github.com/ShannonAI/mrc-for-flat-nested-ner) |       -             |
| Event Detection |  [ACE 2005](https://catalog.ldc.upenn.edu/LDC2006T06)                                              |      [HMEAE](https://github.com/thunlp/HMEAE)               | 

### Train
The detail hyper-parameter setting is listed in our [paper](https://arxiv.org/pdf/2111.00884.pdf).

* For NER task, run `run_ner.py`.
* For Event Detection task, run `run_trigger_extraction.py`



