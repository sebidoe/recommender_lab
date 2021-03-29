# recommender_lab

This project was done for a university course. The overall goal is to recommend papers to a researcher based on an initial input. The system uses BERT transformers from [huggingface](https://huggingface.co/transformers/index.html) to create the embeddings for the data. The embeddings are created on the summaries or the preprocessed summaries. There are two different models we used for the embeddings. [DistilBert](https://huggingface.co/transformers/model_doc/distilbert.html#overview) and [SciBert](https://github.com/allenai/scibert). Afterwards the similarity between the embeddings is calculated using [faiss](https://github.com/facebookresearch/faiss) and euclidean distance.

In our experiments we wanted to test the influence of the models, preprocessing and the time it takes to find similar documents.

Results:
...


The dataset used for this can be found [here](https://www.kaggle.com/neelshah18/arxivdataset/metadata)
