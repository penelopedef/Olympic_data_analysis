## An Analysis of 120 Years of Olympic History
#### Researchers - Penelope DeFreitas and Alexandra
#### Programme - Master of Science in Data Science & Analytics (DSA), Toronto Metropolitan University
#### Course - Data Visualization
#### Purpose - This repository was completed as a graded project in partial fulfillment of the requirements for the MSc DSA degree.

## Dataset Used
- The dataset used in this project was obtained from Kaggle and is publicly available under a Creative Commons (CC) license.
- Dataset URL - https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results
- The dataset contains 271,116 athlete records spanning 120 years of both the Summer and Winter Olympic Games (1896–2016). It includes ~15 key attributes such as:
    - Athlete demographics (e.g., Age, Sex, Height, Weight)
    - Event details (e.g., Sport, Event, Year, NOC)
    - Medal information (Gold, Silver, Bronze)

The key files utilized:
- noc_regions.csv
- athlete_events.csv

## Required Libraries
Make sure to install the following packages in your Colab/virtual environment:
- pandas
- numpy as np
- matplotlib.pyplot
- matplotlib.cm
- matplotlib.patches
- seaborn
- plotly.express

## How to Run the Code

You can execute the project using Google Colab, Jupyter Notebook, or any .ipynb-compatible environment.

1. Download the dataset files from Kaggle and upload them to your Google Drive (same folder as the two .ipynb notebooks — Part 1 and Part 2).
2. Mount Google Drive in Colab:
        from google.colab import drive
        drive.mount('/content/drive')
3. Update the notebook file paths if needed, then run all cells sequentially.
