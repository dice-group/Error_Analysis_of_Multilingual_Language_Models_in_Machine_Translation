# Error Analysis of Multilingual Language Models in Machine Translation: A Case Study of English-Amharic Translation

This repository contains the artifacts for our paper "Error Analysis of Multilingual Language Models in Machine Translation: Amharic as a Case Study." 

## Abstract

Multilingual large language models (mLLMs) have significantly advanced machine translation, yet challenges remain for low-resource languages like Amharic. This study evaluates the performance of state-of-the-art mLLMs, specifically NLLB-200 (NLLB3.3, NLLB1.3 Distilled1.3, NLB600) and M2M (M2M1.2B, M2M418), in English-Amharic bidirectional translation using the Lesan AI dataset. We employed both automatic and human evaluation methods to analyze translation errors. Automatic evaluation used BLEU, METEOR, chrF, and TER metrics, while human evaluation assessed translation quality at both word and sentence levels. Sentence-level accuracy was rated by annotators on a scale from 0 to 5, and word-level quality was evaluated using Multidimensional Quality Metrics. Our findings indicate that the NLLB3.3B model consistently outperformed other mLLMs across all evaluation methods. Common errors included mistranslation, omission, untranslated segments, and additions, with mistranslation being particularly common. Punctuation and spelling errors were rare in our experiment.

## Citation

If you use our work, please cite our paper as follows:

```bibtex
@inproceedings{Hizkiel_2024,
  added-at = {2024-10-11T01:28:47.000+0200},
  author = {Alemayehu, Hizkiel Mitiku and Zahera, Hamada M. and {Ngonga Ngomo}, Axel-Cyrille},
  biburl = {https://www.bibsonomy.org/bibtex/2804f07ae419cfb87c2893feede6f8890/dice-research},
  booktitle = {Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing},
  interhash = {63eba1c9a5c45ca7dac9a29300b218d1},
  intrahash = {804f07ae419cfb87c2893feede6f8890},
  keywords = {TRR318 colide dice enexa hizkiel kiam ngonga zahera},
  publisher = {Association for Computational Linguistics},
  timestamp = {2024-10-14T00:06:36.000+0200},
  title = {Error Analysis of Multilingual Language Models in Machine Translation: A Case Study of English-Amharic Translation},
  url = {https://papers.dice-research.org/2024/EMNLP_Error_Analysis/public.pdf},
  year = 2024
}
