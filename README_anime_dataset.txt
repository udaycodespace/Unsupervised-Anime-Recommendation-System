
# Anime Dataset (anime_2025.csv)

This dataset is used in a Python 3 project for analyzing anime rankings, ratings, genres, and other metadata.

## Source
The original dataset was sourced from Kaggle:
🔗 https://www.kaggle.com/datasets/quanthan/top-15000-ranked-anime-dataset-update-to-32025

## Modifications Made
- Renamed the original file to `anime_2025.csv` for consistency with the project naming conventions.
- Removed the `japanese_name` column entirely, as it was causing parsing errors during data loading.

## Usage
This dataset is loaded using `pandas` in the main Python script:

```python
import pandas as pd

anime_df = pd.read_csv("anime_2025.csv")
```

The dataset includes 15,000 entries and 21 columns, covering key fields such as:
- `name`, `english_name`, `genres`, `score`, `type`, `episodes`, `source`, `rating`, `rank`, `popularity`, etc.

It is primarily used for exploratory data analysis, ranking visualizations, and content filtering based on genre and score.

## File Location
Ensure the `anime_2025.csv` file is placed in the same directory as your Python script or properly referenced if using subdirectories.

