# Reccomendation Systems Final Project
### Applying the two-stage YouTube recommendation system to MovieLens 1M

This project is implementing the model as presented in the [paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45530.pdf) by Covington, Adams and Sargin. Originally, the model tries to recommend the best YouTube videos to a user based on its history. When implemented on the Movielens dataset, we try to recommend the next movie for a user to watch.\
It is recommended to read the [report](https://github.com/ayalaraanan/RecSys-final-project/blob/main/Final%20Project%20Report.pdf) first.

The project is composed of:

A. The main YouTube model, which includes the following notebooks:
1. [Datasets generation for the candidates model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/1_RecSys_final_project_data_generation_for_candidate_model.ipynb)
2. [Candidates model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/2_RecSys_final_project_candidates_model.ipynb)
3. [Datasets generation for the ranking model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/3_RecSys_final_project_data_generation_for_Ranking.ipynb) (using the candidates model output)
4. [Ranking model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/4_RecSys_final_project_Ranking_model.ipynb)

B. A [matrix factorization model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/baseline/RecSys_final_project_youtube_MF_baseline.ipynb), Used as a reference with the same data

C. Suggested improvements including:
1. Integrating [RNN units](https://github.com/ayalaraanan/RecSys-final-project/blob/main/Improvements_RNN/RecSys_final_project_candidates_model_with_RNN.ipynb) for handling viewing history
2. Adding information on transitions from genre to genre in order to anticipate the next movie genre: [data generation](https://github.com/ayalaraanan/RecSys-final-project/blob/main/Improvements_Markov/RecSys_final_project_candidates_model_with_transitions.ipynb
), [model training](https://github.com/ayalaraanan/RecSys-final-project/blob/main/Improvements_Markov/RecSys_final_project_data_generation_for_candidate_model_with_transitions.ipynb)

Further details can be found inside the notebooks and in the [final report](https://github.com/ayalaraanan/RecSys-final-project/blob/main/Final%20Project%20Report.pdf).

## Running the notebooks
There are two ways to use the notebooks:

i. If you wish to modify and run all notebooks yourself, you will need to store the outputs for later use by the other notebooks.
I used google drive for the task.

ii. All of my data files, intermediate results, and results are accessible with gdown. You may need to import and run gdown upgrade (which in Google Colab requires restaring the runtime after first installation).
