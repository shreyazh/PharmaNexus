## 💊 PharmaNexus - Drug Repurposing using Knowledge Graph Embeddings

Drug repurposing methods can identify already approved drugs to treat them efficiently, reducing development costs and time. At the same time, knowledge graph embedding techniques can encode biological information in a single structure that allows users to operate relationships, extract information, learn connections, and make predictions to discover potential new relationships between existing drugs and vector-borne diseases.

**Find the App here :point_right: [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://dr-using-kge.streamlit.app/) and let me know your comments**.

In this project, we compare seven knowledge graph embedding models (TransE, TransR, TransH, UM, DistMult, RESCAL, and ERMLP) applied to Drug Repurposing Knowledge Graph (DRKG), analyzing their predictive performance over seven different vector-borne diseases (dengue, chagas, malaria, yellow fever, leishmaniasis, filariasis, and schistosomiasis), measuring their embedding quality and external performance against a ground-truth.

This work is based on the paper **[Drug Repurposing Using Knowledge Graph Embeddings with a Focus on Vector-Borne Diseases: A Model Comparison](https://link.springer.com/chapter/10.1007/978-3-031-40942-4_8)** as developed by [Shreyash Srivastva](https://www.linkedin.com/in/shreyashsrivastva/) and [Dr. Anshumaan Kumar](https://www.linkedin.com/in/anshumaan-kumar-7a4193281/) for BioHacks Hackathon 2024.

You can find here the data and code used for developing and evaluating the predictive models.

### Repository structure

- **[streamlit_app.py](streamlit_app.py)**: outputs a drug ranking prediction based on a chosen disease and embedding model.
- **[embedding_models](embedding_models)**: includes the outcomes of predictions on specific diseases generated by trained embedding models using the DRKG dataset.
- **[train_embeddings.py](train_embeddings.py)**: trains an embedding model on a given dataset. Predictions can be performed on the results of this training.
- **[predictions.py](predictions.py)**: performs predictions on the already trained embedding models. 

### Environment
The project was developed using Visual Studio Code 1.84 with Python 3.12
