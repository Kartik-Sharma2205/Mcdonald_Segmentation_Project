# McDonald's Market Segmentation
This project aims to perform data segmentation using customer data from McDonald's. By applying segmentation techniques, we can identify distinct customer segments based on various characteristics such as purchasing behavior, preferences, demographics, and more. The resulting segments can then be used to tailor marketing strategies, optimize product offerings, and enhance customer experiences.

## Data Preprocessing
Used libraries - skikit-learn, matplotlib, pandas and numpy. Meticulously examined the McDonald's customer dataset for missing values and erroneous entries, particularly non-numeric data. Through exploratory data analysis (EDA), we gained valuable insights into the dataset's distribution and relationships between variables, ensuring its integrity and readiness for segmentation analysis.

## Dataset
[Click here to download Dataset](https://drive.google.com/file/d/1OexH-CVBBXAdXwuEdeYfguKliMWqNOyl/view?usp=sharing) Contains data of 1453 customers and contains 15 variables.

## Feature Engineering
In this phase, Principal Component Analysis (PCA) was employed to effectively reduce dimensionality and extract essential features from the dataset. By condensing the original features into a smaller set of principal components, PCA facilitated a more efficient representation of the data while retaining its key characteristics.

 __Clustering__:

The k-means clustering algorithm was applied to segment customers based on their attributes. By iteratively assigning data points to clusters and optimizing cluster centroids, k-means grouped similar customers together, enabling the identification of distinct segments within the customer base.

 __Visualization__:

Various graphs and visualizations were generated to gain insights into the clustering results and interpret customer segments effectively. Visualization techniques played a crucial role in understanding the distribution of data points across clusters and assessing the coherence of the identified segments.

## Requirements
Python 3.x pandas numpy matplotlib seaborn scikit-learn 

## How to Run
-- Clone the repository to your local machine.

-- Install the necessary libraries using pip:

    (pip install pandas numpy matplotlib seaborn scikit-learn)
  
-- Run the code in google colab or desktop application.

-- Explore the clustering results and gain insights from the visualizations generated during the analysis.


## Results
[Click here to download Result_File](https://docs.google.com/spreadsheets/d/1lw2IJGWO-9KsWOYRRr9x-1iyfREtLkb1/edit?usp=sharing&ouid=113132853465074771254&rtpof=true&sd=true) Created a new variable, which gives each customer a specific segment.



