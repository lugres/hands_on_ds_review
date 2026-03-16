# Hands-on Data Science tools

This repos contains a review of hands-on Data Science concepts done in 2025, when getting ready to start a job as a data scientist.

## Topics covered:

### **[1. Python, numpy, pandas](./01_general_python_numpy_pandas/)**: Using Python, NumPy, Pandas for data wrangling and analysis.
* Performing high-speed mathematical operations with NumPy library. Reading/writing csv files; working with data structures like Series, DataFrames; cleaning and filtering data; aggregating, reshaping, concatenating, and other transformations of Pandas datasets.
* Real-world datasets were used: US Covid statistics and YouTube channels time-series data.

### **[2. Exploratory Data Analysis (EDA) with Matplotlib and Seaborn](./02_data_visual_descr_stats/)**: Using Matplotlib and Seaborn libraries for visual data analysis.
* Data visualization with histograms and boxplots.
* Continue with descriptive statistics and Exploratory Data Analysis (EDA). 
* Real-world datasets: US Covid statistics, US House prices, real/fake Swiss banknotes, YouTube data.

### **[3. Test statistical hypothesis](./03_testing_stat_hypotheses/)**: Using error types, p-value to check for statistical significance and test hypothesis.

### **[4. Data clustering (K-means)](./)**: Partition data into relatively homogeneous groups, even when data is limited and the requirements of classical statistical analysis methods are not met.

### **[5. Linear, polynomial and logistic regression](./)**: Using different regression methods for predictions. Apply cross-validation, random-fold validation, r2, p-value, train/test splits, confusion matrices, and ROC/AUC to judge about and improve model quality.

### **[6. Principal component analysis (PCA)](./)**: Conduct a principal component analysis (PCA) too structure the relationships between variables.

### **[7. Decision tree classifier, random forests](./)**: Build decision trees and evaluate classifier performance to solve classification and regression problems; improve classifiers with stacking, boosting, and bagging.


## Some visual examples: 

### Covid cases in the US

* [Covid cases by county, WA](./02_data_visual_descr_stats/visuals/covid_cases_by_country_WA.png)
* [Covid cases dynamic by states](./02_data_visual_descr_stats/visuals/covid_cases_dynamic_by_state.png)

### House prices

* [House prices by zones](./02_data_visual_descr_stats/visuals/house_prices_by_zones.png)
* [House prices by zones, boxplot](./02_data_visual_descr_stats/visuals/house_prices_by_zones_boxplot.png): outliers are immediately visible.

### Real and counterfeit Swiss banknotes

* [Real vs counterfeit Swiss banknotes, check all params](./02_data_visual_descr_stats/visuals/real_vs_counterfeit_banknotes_params.png)
* [Real vs counterfeit Swiss banknotes, dig deeper into bimodality (diagonals)](./02_data_visual_descr_stats/visuals/real_vs_counterfeit_diag.png)
* [Real vs counterfeit Swiss banknotes, summary](./02_data_visual_descr_stats/visuals/real_vs_counterfeit_diag_summ.png): diagonal size of a banknote is a key parameter to detect counterfeit.

### YouTube videos

* [Explore views, likes, and dislikes of Youtube videos by date](./02_data_visual_descr_stats/visuals/yt_views_likes_dislikes.png)
* [Explore views, likes, and dislikes - date and category](./02_data_visual_descr_stats/visuals/yt_views_likes_dislikes_catgrs.png)
* [Explore views by category](./02_data_visual_descr_stats/visuals/yt_views_catgrs.png)
* ["Likes by Views" metric, boxplot](./02_data_visual_descr_stats/visuals/yt_likes_by_views_catgrs.png): how many likes do we get for each view, by category.