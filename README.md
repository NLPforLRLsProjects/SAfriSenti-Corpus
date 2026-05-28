# SAfriSenti-Corpus-Mini
A multilingual sentiment corpus for South African Under-Resourced languages.
This corpus includes the following languages: Code-switched Dataset, English, Sepedi, Setswana, and Sesotho.
We are working on extending the corpus to more languages like IsiZulu, Ndebele, Xhosa, Tshonga, Venda and Afrikaans.
We aim to release the dataset in December 2026.
We also aim to collect tweets from nearby countries like Lesotho, Botswana, Swaziland and the Shona language for Zimbabwe

# SAfriSenti-Corpus Licenses
This dataset is currently for a PhD project of Mr Ronny Mabokela enrolled at Wits University, South Africa. It will be licensed and approved within the University. An ethical clearance has been obtained and approved for this research. 

# SAfriSenti-Corpus Focus
This project focuses on developing sentiment resources for South African languages. The dataset will be available for the NLP community for low-resource languages.

# Training Data
We provide the training data for each language, including code-switches, separately.


# Some Results with African LLMS
```Accuracy: 0.7832796713667147
Classification Report:
               precision    recall  f1-score   support

           0       0.78      0.90      0.83      4583
           1       0.59      0.46      0.52       668
           2       0.83      0.69      0.75      3756

    accuracy                           0.78      9007
   macro avg       0.73      0.69      0.70      9007
weighted avg       0.78      0.78      0.78      9007```

```Classification Report:
              precision    recall  f1-score   support

           0       0.68      0.73      0.71       682
           1       0.80      0.82      0.81      3820
           2       0.85      0.83      0.84      4505

    accuracy                           0.82      9007
   macro avg       0.78      0.79      0.79      9007
weighted avg       0.82      0.82      0.82      9007```

```Classification Report:
              precision    recall  f1-score   support

           0       0.53      0.68      0.59       671
           1       0.45      0.19      0.26       707
           2       0.64      0.76      0.70      1175

    accuracy                           0.58      2553
   macro avg       0.54      0.54      0.52      2553
weighted avg       0.56      0.58      0.55      2553```

```Classification Report:
              precision    recall  f1-score   support

           0       0.68      0.77      0.72      1262
           1       0.73      0.62      0.67      1334
           2       0.79      0.80      0.79      2445

    accuracy                           0.74      5041
   macro avg       0.73      0.73      0.73      5041
weighted avg       0.75      0.74      0.74      5041```

```Classification Report:
              precision    recall  f1-score   support
           0       0.47      0.54      0.50       298
           1       0.55      0.35      0.43       578
           2       0.66      0.78      0.71       924
    accuracy                           0.60      1800
   macro avg       0.56      0.56      0.55      1800
weighted avg       0.59      0.60      0.59      1800 ```

# References
1. Mabokela, K. R., & Schlippe, T. (2022). A sentiment corpus for South African under-resourced languages in a multilingual context. In *Proceedings of SIGUL 2022 @ LREC 2022* (pp. 70–77). European Language Resources Association.

2. Mabokela, K. R., Schlippe, T. (2022). AI for social good: Sentiment analysis to detect social challenges in South Africa. In *Artificial Intelligence Research* (pp. 309–322). Springer Nature Switzerland.

3. Mabokela, K. R., Raborife, M., & Celik, T. (2023). Investigating sentiment-bearing words- and emoji-based distant supervision approaches for sentiment analysis. In *Proceedings of the Fourth Workshop on Resources for African Indigenous Languages (RAIL 2023)* (pp. 115–125). Association for Computational Linguistics. https://doi.org/10.18653/v1/2023.rail-1.13

4. Mabokela, K. R., Celik, T., & Raborife, M. (2023). Multilingual sentiment analysis for under-resourced languages: A systematic review of the landscape. *IEEE Access, 11*, 15996–16020. https://doi.org/10.1109/ACCESS.2022.3224136

5. Mabokela, K. R., Primus, M., & Celik, T. (2024). Explainable pre-trained language models for sentiment analysis in low-resourced languages. *Big Data and Cognitive Computing, 8*(11), 160. https://doi.org/10.3390/bdcc8110160

6. Mabokela, K. R., Primus, M., & Celik, T. (2025). Advancing sentiment analysis for low-resourced African languages using pre-trained language models. *PLOS ONE, 20*(6), e0325102. https://doi.org/10.1371/journal.pone.0325102

## Citation

If you use **SAfriSenti-Corpus-Mini** in your research, please cite the relevant SAfriSenti publications as follows:

```bibtex
@inproceedings{mabokela2022safrisenti,
  author    = {Mabokela, Koena Ronny and Schlippe, Tim},
  title     = {A Sentiment Corpus for South African Under-Resourced Languages in a Multilingual Context},
  booktitle = {Proceedings of the First Workshop on Resources and Representations for Under-Resourced Languages and Domains},
  year      = {2022}
}

@inproceedings{mabokela2023distant,
  author    = {Mabokela, Koena Ronny and Schlippe, Tim},
  title     = {Investigating Sentiment-Bearing Words- and Emoji-Based Distant Supervision Approaches for Sentiment Analysis},
  booktitle = {Proceedings of the Workshop on Resources for African Indigenous Languages},
  year      = {2023}
}

@article{mabokela2024xai,
  author  = {Mabokela, Koena Ronny and Primus, Mpho and Celik, Turgay},
  title   = {Explainable Pre-Trained Language Models for Sentiment Analysis in Low-Resourced Languages},
  journal = {Big Data and Cognitive Computing},
  year    = {2024}
}

@article{mabokela2025safrisenti,
  author  = {Mabokela, Koena Ronny and Primus, Mpho and Celik, Turgay},
  title   = {Advancing Sentiment Analysis for Low-Resourced African Languages Using Pre-Trained Language Models},
  journal = {PLOS ONE},
  year    = {2025}
}
```

# Recommended Dataset Citation

```bibtex
@misc{mabokela2026safrisenti_mini,
  author       = {Mabokela, Koena Ronny and Primus, Mpho and Celik, Turgay},
  title        = {{SAfriSenti-Corpus-Mini}: Multilingual Sentiment Corpus for South African Under-Resourced Languages},
  year         = {2026},
  howpublished = {GitHub repository},
  note         = {Balanced sample containing 1,500 labelled sentiment records across Sepedi, Sesotho, Setswana, isiXhosa, and isiZulu},
  url          = {https://github.com/NLPforLRLsProjects/SAfriSenti-Corpus}
}
```
