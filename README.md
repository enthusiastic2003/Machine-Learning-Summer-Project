# Data Analytics and Machine Learning Tool

You can explore the deployed tool [HERE](https://automaticmltool.onrender.com/), though please note it may load slowly.

## Our Team
1. Sirjan Hansda
2. Aastha Verma
3. Ayush Raina
4. Saivinayak

## Objective
This tool is designed to empower users without prior knowledge of Machine Learning to train models and generate predictions with ease. Users simply need a dataset to begin, and the tool’s layout has been crafted to be both intuitive and visually appealing. In addition to model training, this tool offers extensive features for data analysis, enabling users to visualize data trends and patterns through various graphical tools.

## Setup and Installation
1. First, clone the project repository by running:  
git clone https://github.com/ayushraina2028/Data-Analytics-and-Machine-Learning-Tool.git

After pressing **Enter**, the repository will be cloned to your local system.
2. Next, install the dependencies listed in the requirements file by running:
pip install -r requirements.txt

This will automatically install all required packages.
3. To start, we have provided two example datasets: `winequalityN.csv` (for classification tasks) and `real_estate.csv` (for regression tasks).
4. Run the application by executing `app.py`. You can do this in VS Code using the run button or by entering:
python app.py

The program may take a few seconds to initialize and will generate three links; click on the third one to access the app in your browser.

## How to Use
On the **Home Page**, you'll find our team’s contact links. Click on the **START** button to proceed.

1. The introductory page provides an overview of the tool’s functionality; click **Let's Start** to continue.
2. Upload a dataset to begin. You can use one of the provided datasets or upload your own, but ensure it is from a reliable source to avoid potential errors from corrupted data.
3. For example, if you upload the `winequalityN` dataset, hit **Upload** to proceed.

### Phase 1: Data Processing
The tool offers several data processing options:
1. **Data Insights I**: Provides basic metrics about the dataset.
2. **Data Insights II**: Displays detailed statistical information.
3. **Visualization I**: Generates a correlation heatmap and allows you to plot up to nine histograms at once for selected features, helping you analyze data distribution.
4. **Categorical Analysis**: Provides metrics on categorical features and a histogram generator for distribution analysis.

Once you've explored these options, proceed to the next phase: **Missing Value Analysis**.

### Phase 2: Missing Value Analysis
1. This phase presents a table listing features with missing values, the number of missing entries, and their percentages.
2. A bar plot visualizes missing values across features.
3. For categorical features, click **Fill Here** to automatically fill missing values with the mode (most frequent) value.
4. For numerical features, select the "type" column, and boxplots will illustrate the median and outliers. You can then impute missing values by selecting rows where the "type" matches, filling gaps based on the median value for each category.

### Encoding Categorical Features
After handling missing values, proceed to encode categorical features into numerical representations. For instance, in the `winequalityN` dataset, the "type" column contains categories like "red" and "white." Enter numeric values corresponding to each category, confirm changes, and check the dataset to ensure encoding is complete.

### Visualization Pro Max
This section provides a range of advanced visualization options:
1. Plot two graphs at a time from seven available types, including scatter plots, line plots, bar plots, box plots, violin plots, heatmaps, and hexbin plots.
2. Additionally, create pie charts for specific features or grouped bar plots for visualizing relationships between the target variable and two features—ideal for analyzing well-structured data.

## Machine Learning Introduction

### Train-Test Split
After exploring data insights, move to the Machine Learning section:
1. Enter the test size as a decimal between 0 and 1.
2. Choose the problem type: Regression or Classification.
3. Select the target feature for prediction and training features. You can select all features or experiment with different combinations.
4. Based on your selection, you’ll be shown algorithms suitable for your problem type (Classification or Regression).

### Algorithms
For Regression, you’ll see a list of available algorithms:
1. Select either one algorithm or multiple algorithms to compare their performance.
2. When selecting all algorithms, you can compare their accuracy after training on the test data.
3. For single algorithm selection, each algorithm has a dedicated page where you can **train**, **test**, and **predict**. After training, you can check the test accuracy or experiment with hyperparameters to optimize performance.

### Predictions
1. To make predictions, select an algorithm and navigate to its dedicated page.
2. Start training, and once complete, input fields will appear for new data.
3. Enter new data points and click **Predict** to generate predictions.

