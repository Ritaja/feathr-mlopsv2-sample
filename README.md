## Create the necessary environment

- Make sure you have conda/miniconda installed on your machine

- Create a new conda environment and activate it

```bash
conda create -f environment.yml
conda activate datascience-env
```

## Upload data

- navigate to the `data` folder and locate the `nyc_taxi.parquet` file

- Navigate to Azure Portal and open the storage account you created in the previous step(s)

- Click on "Container" and then click on "+ Container", name the container `nyctaxi` and upload the data `nyc_taxi.parquet` file to this new container

## Run the notebook
- A notebook is provided in this folder to help you get started with the feature store. Open the notebook and follow the instructions in the notebook to get started. THe notebook is named `nyc_taxi_demo.ipynb`

- The Feathr config file is provided in this folder as well, it is named `feathr_config.yml`. You will not need to change the values in this file, most of the required parameters for this exercise will be set from the notebook as environment variables.