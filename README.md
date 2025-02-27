import pandas as pd

# Load the dataset
anime_df = pd.read_csv('Anime.csv')

# Display basic information about the dataset
info = anime_df.info()

# Display the first few rows of the dataset
head = anime_df.head()

# Display summary statistics of the dataset
describe = anime_df.describe()

info, head, describe
