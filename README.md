# Enhancing Language Models for Financial Relation Extraction with Named Entities and Part-of-Speech

This repository contains the data and codes for the ICLR 2024 Tiny Paper titled ["Enhancing Language Models for Financial Relation Extraction with Named Entities and Part-of-Speech"](https://openreview.net/pdf?id=BAR6OE80OW) by Menglin Li and Kwan Hui Lim.

# Abstract

The Financial Relation Extraction (FinRE) task involves identifying the entities and their relation, given a piece of financial statement/text. To solve this FinRE problem, we propose a simple but effective strategy that improves the performance of pre-trained language models by augmenting them with Named Entity Recognition (NER) and Part-Of-Speech (POS), as well as different approaches to combine these information. Experiments on a financial relations dataset show promising results and highlights the benefits of incorporating NER and POS in existing models.
Our dataset and codes are available at https://github.com/kwanhui/FinRelExtract.

# Acknowledgement

This work is based on the [REFinD dataset](https://arxiv.org/abs/2305.18322) and utilizes the publicly available implementations of various models, as referenced in our paper. We thank the authors of these codes and dataset.

# Reference

If you find this code useful or use it in your work, please consider citing:
```
@INPROCEEDINGS { Li-ICLR24,
	AUTHOR = {Menglin Li and Kwan Hui Lim},
	TITLE = {{Enhancing Language Models for Financial Relation Extraction with Named Entities and Part-of-Speech}},
	BOOKTITLE = {{Proceedings of the Twelfth International Conference on Learning Representations (ICLR'24), Tiny Paper Track}},
	MONTH = {May}, 
	YEAR = {2024}
}
```
