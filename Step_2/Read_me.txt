first execute spatial analysis notebooks folder 1_spatial in this order:

1. city_block_features -> analyze spatial features in Bogotá.
2. Moran_I -> calculate spatial correlation by means of Moran I for features.

then execute Machine Learning preparation ML prep notebooks folder 2_ML_Preps:
1. UTAMClusteringPrep -> Prepare DataFrames to execute Clustering.
2. Custering_Silhouette_Test -> execute silhouette test to define Clustering scheme
3. classification_CityBlock_prep ->prepare DataFrames to execute classification
4. city_block_classification_test -> compare different classification schemes 
