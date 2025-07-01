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
