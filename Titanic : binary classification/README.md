## Titanic. Binary Classification

In this project, in addition to working in Jupyter Notebook, I also built model in Azur.



![Снимок экрана 2023-03-02 в 22 06 41](https://user-images.githubusercontent.com/85711789/222557664-990881bd-3271-44ee-9fe6-5fe10f6b6c33.png)


> For it I:
* Imported Titanic dataset into the workspace using a CSV file from Github: https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv
* Used the dataset to create a new dataset in the workspace by retrieving data from a URL 
and copying the data sets into the storage account under the workspace.
* Designed the model using components: `clean_missing_data`, `select_columns_in_dataset`, `split_data`, `two_class_boosted_decision_tree`,
`train_model`, `score_model`, `evaluate_model`.


### The resulting model has the following metrics 

![Снимок экрана 2023-03-02 в 22 03 01](https://user-images.githubusercontent.com/85711789/222561740-3d716868-a29a-4bf0-9939-7c3f74fddb6a.png)


### I also examined what results the  automated ML would give out 

![Снимок экрана 2023-03-02 в 22 48 36](https://user-images.githubusercontent.com/85711789/222564931-e96b03ea-bda1-4fd8-92de-15297da24a94.png)
