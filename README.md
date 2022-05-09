# CalibrationFair
Calibration Fairness

## Dataset Preprocessing Pipeline
1. Downloading datasets raw file (`datasets/DS_NAME/raw`)
2. Collecting required features and mapping IDs to range `0` - `N` (the number of users or items). To do this we provide each dataset a specific notebook (`datasets/DS_NAME/DS_Name_dataset.ipynb`)
    - __Output__: Here we create two file, one for the `rating` data which show a user's rating on an item, and another one is `cat` file. The `cat` file indicate the category of each item (`datasets/DS_NAME/DS_NAME_data_map.txt` and `datasets/DS_NAME/DS_NAME_cat_map.txt`).
3. `dataset.ipynb` ---> `datasets/DS_NAME/DS_NAME_data.txt` and `datasets/DS_NAME/DS_NAME_cat.txt`
4. 

## Datasets

- ClothingFit: 5-core
