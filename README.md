# SPE_Showcase_GenrePredict
Repository for the SPE Data Science Showcase

Within this repository is the workflow for building a Predictive Model for Movie Genres from a dataset extracted from the IMDB platform.

** The evaluation criteria are present in the following notebooks:** 

1. Exploratory Data Analysis (EDA):
   - 1-IMDB_EDA_Database.ipynb
2. Machine Learning Model Development:
   - 2-IMDB_Create_Database
   - 3-IMDB_LSTM_2Layers_US
   - 4-IMDB_LGBM_US
3. Inference and Submission:
   - 3-IMDB_LSTM_2Layers_US
   - 4-IMDB_LGBM_US
   

**The repository organization is as follows:**

- At the root of the repository are the notebooks and necessary resources for their operation that are not databases, in our case, notebooks and the pre-trained GloVe model.
- In the input folder, we have the dataset subfolder containing the datasets provided by the SPE, and also within the input folder, we have the databases constructed by the notebooks that will be used by the predictive model notebooks.
- In the output folder, we have the two output files for genre inference for the test dataset provided by the SPE.


The draft below demonstrates the workflow and the components of this repository.

![image](https://github.com/cmatos17/SPE_Showcase_GenrePredict/assets/43851217/13706266-176a-4e58-a144-17d0cdfa72bd)
