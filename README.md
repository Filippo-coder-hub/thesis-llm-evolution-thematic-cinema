# thesis-llm-evolution-thematic-cinema
Data-driven analysis of thematic evolution in mainstream cinema (1980–2020)

Repository ufficiale della tesi magistrale di Filippo Sgarabotto.

## Descrizione

Questo progetto analizza l’evoluzione delle configurazioni tematiche nel cinema mainstream statunitense tra il 1980 e il 2020 attraverso un approccio data-driven applicato ai sottotitoli dei film.

L’impianto metodologico integra:

- Preprocessing testuale su corpus di sottotitoli
- Classificazione tematica tramite Large Language Models (LLM)
- Costruzione di un indicatore di salienza narrativa (0–10)

L’analisi è stata sviluppata in ambiente Deepnote (Python).

## Struttura della repository

- `notebooks/` → Notebook completi per preprocessing, modeling e analisi
- `data/` → Dataset utilizzati (metadata)
- `results/` → Output LLM e risultati aggregati finali

## Riproducibilità

La repository contiene:

- Codice esecutivo completo
- Prompt utilizzati per l’interrogazione dei modelli LLM
- Dataset finali utilizzati nell’analisi
- Output aggregati delle misurazioni di salienza

I parametri tecnici del modello (LLM, temperature, seed) sono specificati nel Capitolo 2 della tesi.
