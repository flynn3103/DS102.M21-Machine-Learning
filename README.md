# DS102.M21-Machine-Learning

Install project requirements by using:

`conda create --name ml_ediotr --file requirements.txt`

The library uses a few models from spacy. To download the small and large
English model (required to run the app and the notebooks), run these commands
from a terminal with your virtualenv activated:

`python -m spacy download en_core_web_sm`

`python -m spacy download en_core_web_lg`

### Data Preparation
- Download a subfolder from the stackoverflow [archives][archives]

- Run `parse_xml_to_csv` to convert it to a DataFrame

- Run `generate_model_text_features` to generate a DataFrames with precomputed features

[archives]: https://archive.org/details/stackexchange

The notebooks belong to a few categories of concepts, described below.

### Data Exploration and Transformation

- [Dataset Exploration][DatasetExploration]
- [Splitting Data][SplittingData]
- [Vectorizing Text][VectorizingText]
- [Clustering Data][ClusteringData]
- [Tabular Data Vectorization][TabularDataVectorization]
- [Exploring Data To Generate Features][ExploringDataToGenerateFeatures]

### Initial Model Training and Performance Analysis

- [Train Simple Model][TrainSimpleModel]
- [Comparing Data To Predictions][ComparingDataToPredictions]
- [Top K][TopK]
- [Feature Importance][FeatureImportance]
- [Black Box Explainer][BlackBoxExplainer]

### Improving the Model

- [Second Model][SecondModel]
- [Third Model][ThirdModel]

### Model Comparison

- [Comparing Models][ComparingModels]

### Generating Suggestions from Models

- [Generating Recommendations][GeneratingRecommendations]

[BlackBoxExplainer]: ./black_box_explainer.ipynb
[ClusteringData]: ./clustering_data.ipynb
[ComparingDataToPredictions]: ./comparing_data_to_predictions.ipynb
[ComparingModels]: ./comparing_models.ipynb
[DatasetExploration]: ./dataset_exploration.ipynb
[ExploringDataToGenerateFeatures]: ./exploring_data_to_generate_features.ipynb
[FeatureImportance]: ./feature_importance.ipynb
[GeneratingRecommendations]: ./generating_recommendations.ipynb
[SecondModel]: ./second_model.ipynb
[SplittingData]: ./splitting_data.ipynb
[TabularDataVectorization]: ./tabular_data_vectorization.ipynb
[ThirdModel]: ./third_model.ipynb
[TopK]: ./top_k.ipynb
[TrainSimpleModel]: ./train_simple_model.ipynb
[VectorizingText]: ./vectorizing_text.ipynb
