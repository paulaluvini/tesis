# Artificial intelligence tools in the fight against digital gender-based violence: a study focusing on Rio de la Plata Spanish.

This repository contains the code and data used in the thesis titled **Artificial intelligence tools in the fight against digital gender-based violence: a study focusing on Rio de la Plata Spanish.**. The study aims to develop a model that identifies various types of sentiment in tweets directed at women involved in politics and public affairs, in order to analyze the digital violence they face. The full thesis is available in Spanish [here](https://repositorio.udesa.edu.ar/items/bced2c64-f572-4ed2-8206-9e0925d02d84).

## Context
Abuse and digital violence on social networks such as Twitter, Facebook, and WhatsApp have gained significant relevance in recent years. Women and other feminized identities experience high rates of online harassment, impacting their mental health and political participation. To address this issue, a labeled dataset was created with tweets directed at women in politics in Uruguay.

## Dataset
The dataset was developed as part of a project by **UNDP Uruguay**, the **National Institute for Women of the Government of Uruguay**, and the **British Embassy in Montevideo**.

- **9,000 tweets** were annotated, selected both randomly and through *active learning*.
- Each tweet was classified by two groups of Uruguayan annotators based on:
  - Whether it was directed at a woman in politics.
  - Whether it was abusive, critical, neutral, positive, or counter-abusive.
- *Agreement* between annotators was evaluated to validate the quality of annotations.

## Models Used
Several pre-trained *transformer* models were tested:
- **BERT**
- **RoBERTa**
- **Robertuito**
- **ELECTRA**
- **Bertin**

The best performance on the validation dataset was achieved by **Robertuito**, which was used for the final analysis and a detailed error evaluation.

## Repository Structure
```
├── data/              # Dataset (protected for privacy reasons)
├── models/            # Trained models (protected for privacy reasons)
├── notebooks/         # Jupyter Notebooks with analysis and training
├── figs/              # Evaluations and visualizations
└── README.md          # This file
```

## Contact
For inquiries about this work, you can contact me at luvinipaula@gmail.com

