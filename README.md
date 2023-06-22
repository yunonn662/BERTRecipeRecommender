# BERTRecipeRecommender
## Source of Dataset
- Dataset used to train BERT Cuisine Classifier is from [Kaggle](https://www.kaggle.com/datasets/kaggle/recipe-ingredients-dataset).
- Dataset used to train Doc2Vec model is from [Recipes Box](https://eightportions.com/datasets/Recipes/#fn:1).

## Dataset, Models and Embeddings Download Link
- [GoogleDrive](https://drive.google.com/drive/folders/1yxRw-5uVD2kBiWF8KQnTCV8hwqu1lDwb?usp=sharing)

### Reference
The idea is from a [Medium](https://towardsdatascience.com/a-recommendation-engine-that-proposes-recipes-after-taking-photos-of-your-ingredients-de2d314f565d) tutorial.

- Instead of using LogisticRegressionCV to predict the type of cuisine, I wanted to replace it with Bidirectional Encoder Representations from Transformers(BERT) language model.
- This project was a part of my university group assignment for the course WID3002 Natural Language Processing where the application was named [RecRes](https://github.com/nwjun/RecRes).
