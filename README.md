# GHTM-Graph-based-Hybrid-Topic-Modeling
This repo contains the work behind the paper: GHTM: A Graph based Hybrid Topic Modeling Approach in Low-Resource Bengali Language

## 📌 Overview

GHTM model consists of three stages. 
- First, text features are extracted using a combination of TF-IDF and GloVe representations.
- The second stage constructs a graph from the extracted vectors, which is then processed by a graph convolutional network (GCN) to produce similarity-aware embeddings.
- Finally, matrix factorization is applied to the embeddings to generate diverse and coherent topic keywords.

This hybrid approach helps GHTM uncover coherent, structure-aware latent topics.


## ⚙️ Installation

```bash
git clone https://github.com/kya602/GHTM-Graph-based-Hybrid-Topic-Modeling.git
cd GHTM-Graph-based-Hybrid-Topic-Modeling

pip install -r requirements.txt


## Prepare Data
jupyter notebook GHTM/Data Preparation.ipynb

This is a reference notebook for preparing data.

## Models and Files Placement
- Find the GloVe models for Bangla here: https://github.com/sagorbrur/GloVe-Bengali
- Place the model here: GHTM/model/

## Train the model
jupyter notebook GHTM/GHTM.ipynb

This notebook shows how to train the model for topic modeling and generate topic words. It also shows how to evaluate the model.
