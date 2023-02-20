# sdp_food
Predict recipe rating from recipe dataset

## Python environment
Create a conda environment with

`conda create -n sdp_food python`

, activate the environment with

`conda activate sdp_food`

and install the relevant packages with

`pip install -r requirements.txt`

## Data
In order to download data from Kaggle, complete the following steps
- Create a Kaggle account at https://kaggle.com
- Download a 'kaggle.json' file by going to 'Account' -> 'Create new API token'
- Create a '.kaggle' directory in your home folder
- Put the downloaded 'kaggle.json' in the '~/.kaggle' directory
- Run the 'get_data.py' python file, which creates a new 'data' folder including four files: 'recipes.csv', 'recipes.parquet', 'reviews.csv', 'reviews.parquet'

