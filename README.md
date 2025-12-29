# Global disparities and structural imbalances in AI integration for urban climate resilience research

This repository contains the source code and datasets used to analyse scientific abstracts (specifically within the domain of **Urban Climate Resilience**). 

The project employs a two-stage pipeline:

1.  **AI Detection:** Using Large Language Models (LLMs) to classify whether an abstract utilises Artificial Intelligence methods.
2.  **Topic Modelling:** Applying BERTopic to cluster the identified literature into semantic topics.

## Repository Structure

```text
├── data/
│   ├── Selected_literature_all.zip        # Compressed dataset of all abstracts
│   └── BERTtopic_frequency.csv            # Topic frequency results
├── script/                    
│   ├── 01_LLM_binary_classification.ipynb # Notebook for AI detection using LLMs
│   └── 02_BERTopic.ipynb                  # Notebook for topic modelling and visualisation
├── README.md                              # Project documentation      
