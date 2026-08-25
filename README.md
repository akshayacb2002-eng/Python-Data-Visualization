# Python-Data-Visualization
Python Data Analytics assignment focused on data cleaning and visualization using Pandas, Matplotlib, and Seaborn with the Seaborn Taxis dataset.

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The assignment uses the built-in Seaborn `taxis` dataset.

The dataset contains information related to taxi trips, including:

- Pickup time
- Distance
- Fare
- Tip
- Tolls
- Total
- Payment method
- Pickup zone
- Pickup borough
- Dropoff information

## Data Cleaning

The assignment includes handling missing values by:

- Checking for missing values
- Identifying columns containing missing data
- Using appropriate strategies for numerical columns
- Using mode for categorical columns
- Removing rows when critical values cannot reasonably be imputed

## Visualizations

### Visualizations using Matplotlib / Pandas

#### 1. Line Chart
Visualizes fare over time using:

- `pickup` as the x-axis
- `fare` as the y-axis

#### 2. Bar Chart
Shows the total fare for each `pickup_borough`.

#### 3. Pie Chart
Shows the distribution of trips based on payment method.

#### 4. Histogram
Shows the distribution of taxi trip distances using customized bins.

#### 5. Box Plot
Shows the distribution of tip amounts for each `pickup_borough`.

### Visualizations using Seaborn

#### 6. Count Plot
Shows the number of trips in each `pickup_borough`.

#### 7. Scatter Plot
Shows the relationship between `distance` and `fare`, with the points differentiated by `pickup_borough`.

#### 8. Heatmap
Shows the correlation between numerical variables such as:

- Distance
- Fare
- Tip
- Tolls
- Total

#### 9. Pair Plot
Shows pairwise relationships between:

- Distance
- Fare
- Tip
- Total

The data points are colored according to `pickup_zone`.

#### 10. Violin Plot
Shows the distribution of fare for each payment method.

## Key Concepts Covered

- Data loading
- Data exploration
- Missing-value handling
- Data cleaning
- GroupBy operations
- Data aggregation
- Matplotlib visualization
- Pandas plotting
- Seaborn visualization
- Correlation analysis
- Distribution analysis
- Relationship analysis

## Visualizations Included

1. Line Chart
2. Bar Chart
3. Pie Chart
4. Histogram
5. Box Plot
6. Count Plot
7. Scatter Plot
8. Heatmap
9. Pair Plot
10. Violin Plot
