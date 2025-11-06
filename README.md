## An Analysis of 120 Years of Olympic History
#### Researchers - Penelope DeFreitas and Alexandra
#### Programme - Master of Science in Data Science & Analytics (DSA), Toronto Metropolitan University
#### Course - Data Visualization
#### Purpose - This repository was completed as a graded project in partial fulfillment of the requirements for the MSc DSA degree.

## Background to the Study 
Athletic performance is shaped by a complex interplay of factors, including physical attributes, training regimens (Boullosa et al., 2020), and external conditions (TrineOnline, 2022). Through an in-depth analysis of historical Olympic data, this study aims to identify meaningful patterns across a range of sports disciplines. Specifically, we will examine variables such as age, gender, weight, height, nationality, and event type to uncover performance trends. These insights aim to inform strategies for enhancing athlete development and equity in competition.
The enduring pursuit of excellence in sports has driven ongoing innovation in training techniques and performance analysis. A comprehensive understanding of the factors influencing athletic outcomes empowers athletes, coaches, and sports organizations to make evidence-based decisions that optimize training and maximize performance. Moreover, examining over a century of Olympic data offers a unique opportunity to observe the evolution of athletic achievements, highlight persistent trends, and identify emerging patterns that contribute to success. This research not only enhances our knowledge of elite performance but also reveals areas for future growth and improvement in the global sporting landscape.

## Research Questions
To define the scope of this study, the team refined the research focus by formulating the following guiding questions:
- What key factors influence an athlete's performance?
- Which countries have improved the most in terms of medal performance?
- How have Olympic sports evolved over time in terms of athlete demographics, performance, and competition trends?

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
