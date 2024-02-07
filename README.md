# Amazon Reviews Analysis
Project I used to get comfortable with data analysis technologies.
This Python script analyzes Amazon reviews using the Kaggle dataset "Amazon Sales Dataset." The analysis focuses on the relationship between product ratings and the corresponding number of ratings received.

## Prerequisites

- Python 3.x installed on your machine.
- Required Python packages can be installed using the following command:

  ```bash
  pip install numpy pandas matplotlib seaborn
  ```

## Dataset

The script uses the "Amazon Sales Dataset," which includes information about various products, their ratings, and user reviews. The dataset is loaded from the file `/kaggle/input/amazon-sales-dataset/amazon.csv`.

## Analysis Overview

The script performs the following analyses:

1. **Data Cleaning:**
   - Removal of rows with missing values in the 'rating_count' column.

2. **Data Transformation:**
   - Conversion of 'rating' and 'rating_count' columns to appropriate numerical formats.

3. **Visualization:**
   - Creation of a scatter plot to visualize the relationship between product ratings and the corresponding number of ratings.
   - Axis labels and title for clear interpretation.

## Usage

Run the script by executing the provided code. The analysis results will be displayed in a scatter plot, showing the distribution of ratings against the number of ratings received.

```bash
python amazon_reviews_analysis.py
```

## Notes

- Ensure the dataset file `amazon.csv` is present in the specified directory.
- Check the scatter plot for insights into how the ratings of products correlate with the number of ratings they have received.

Feel free to modify and extend the script for further analysis or additional visualizations based on your specific research questions.
