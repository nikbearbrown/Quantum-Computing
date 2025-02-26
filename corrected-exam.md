# NFO 7390 - Exam 2

## Question 1
**Which of the following statements about probability distributions are correct?**

Group of answer choices:
- A Poisson distribution is used to model the number of occurrences of an event in a fixed interval of time or space.
- The Normal distribution is always skewed to the right.
- A Uniform distribution assigns equal probability to all outcomes within a specified range.
- The Binomial distribution models the probability of a fixed number of successes in independent Bernoulli trials.
- All probability distributions are symmetric.

**Correct Answer: A, C, D**

**Explanation:**
- Poisson distribution is used for modeling count-based events over a fixed time/space interval.
- The Normal distribution is symmetric, not always skewed.
- Uniform distribution assigns equal probabilities within a range.
- Binomial distribution describes the number of successes in independent Bernoulli trials.
- Not all probability distributions are symmetric (e.g., Poisson, Exponential).

## Question 2
**Which statements accurately describe methods of handling missing data?**

Group of answer choices:
- Mean imputation always improves the accuracy of a dataset.
- K-Nearest Neighbors (KNN) imputation estimates missing values based on feature similarity.
- Multiple Imputation by Chained Equations (MICE) creates multiple datasets with different plausible values for missing data.
- Removing missing data is always the best approach.
- Forward fill is a common technique for handling missing data in time series.

**Correct Answer: B, C, E**

**Explanation:**
- KNN imputes missing values by finding similar records.
- MICE models missing values iteratively using other variables.
- Forward fill is useful for time series when missing values occur in sequences.
- Mean imputation can distort variance and relationships.
- Removing missing data is not always ideal, especially with significant missingness.

## Question 3
**Which of the following statements about feature engineering are true?**

Group of answer choices:
- One-hot encoding is useful for converting categorical variables into numerical form.
- Log transformation can help reduce the skewness of highly skewed data.
- Creating interaction terms between features can help capture non-linear relationships.
- Feature selection is unnecessary if all features contain some information.
- Standardizing features is particularly useful for algorithms that use distance metrics.

**Correct Answer: A, B, C, E**

**Explanation:**
- One-hot encoding converts categorical variables into binary columns for modeling.
- Log transformation stabilizes variance in skewed data.
- Interaction terms allow models to capture relationships between variables.
- Feature selection is necessary to reduce noise and improve efficiency.
- Standardization is critical for algorithms like KNN and SVM that rely on distance metrics.

## Question 4
**What are the benefits of Principal Component Analysis (PCA)?**

Group of answer choices:
- Reduces dimensionality while preserving important variance.
- Improves computational efficiency by reducing the number of features.
- Ensures perfect class separability.
- Works best with categorical variables without transformation.
- Helps in visualizing high-dimensional data.

**Correct Answer: A, B, E**

**Explanation:**
- PCA reduces dimensionality by projecting data onto fewer components that retain most variance.
- It speeds up computations by reducing the number of input features.
- It is useful for visualization, especially in two- or three-dimensional space.
- It does not ensure perfect class separability or work well with raw categorical variables.

## Question 5
**Which of the following describe supervised learning techniques?**

Group of answer choices:
- Logistic regression is useful for binary classification problems.
- Decision trees split data using entropy or Gini impurity.
- K-Means clustering is a type of supervised learning algorithm.
- Neural networks can be used for both regression and classification tasks.
- Linear regression is only applicable for discrete data.

**Correct Answer: A, B, D**

**Explanation:**
- Logistic regression is a standard binary classification model.
- Decision trees split data using metrics like entropy or Gini impurity.
- Neural networks are highly flexible and can be used for multiple tasks.
- K-Means is an unsupervised learning technique.
- Linear regression is applicable to continuous data.

## Question 6
**Which statements correctly interpret the boxplot?**

Group of answer choices:
- The "2seater" class has a higher third quartile (Q3) than the "midsize" class.
- The range (difference between maximum and minimum values) for the "midsize" class is greater than that of the "minivan" class.
- The "suv" class has the most outliers compared to other classes.
- The "pickup" class has a smaller IQR than the "minivan" class.
- The "subcompact" class has both the highest median and the largest interquartile range (IQR).

**Correct Answer: A, B, C**

**Explanation:**
- The "2seater" class has a higher third quartile (Q3) than the "midsize" class. The Q3 value for the "2seater" class is visibly higher than the Q3 for the "midsize" class.
- The range for the "midsize" class is greater than that of the "minivan" class. The whiskers for the "midsize" class span a larger range.
- The "suv" class has the most outliers compared to other classes. The "suv" class displays more data points beyond the whiskers.
- The "pickup" class does NOT have a smaller IQR than the "minivan" class. The IQR of the "pickup" class is slightly larger.
- The "subcompact" class has the highest median, but NOT the largest IQR. The "midsize" class has a larger IQR.

## Question 7
**Which of the following statements accurately describe effective data cleaning approaches in data analysis and machine learning?**

Group of answer choices:
- Data cleaning typically involves the removal of duplicate records to prevent skewed analysis and biased results.
- Handling missing values by using imputation techniques, such as mean imputation or multiple imputation, can prevent the loss of valuable data that might be excluded if complete case analysis is used.
- Standardizing data (transforming data to have zero mean and unit variance) is only beneficial for algorithms based on distance calculations, like k-means clustering and k-nearest neighbors.
- Normalizing data, such as scaling attributes to a range of 0 to 1, is unnecessary if machine learning algorithms are not sensitive to the magnitude of variables.
- Outlier detection and treatment is a crucial step in data cleaning, as outliers can significantly affect the results of many statistical analyses and machine learning models.

**Correct Answer: A, B, E**

**Explanation:**
- Removing duplicate records prevents skewed analysis and biased results.
- Imputation techniques prevent data loss and preserve sample size, critical for robust analysis.
- Standardization is beneficial for many algorithms, not just distance-based ones.
- Normalization is often critical even for algorithms not explicitly magnitude-sensitive.
- Outlier detection and treatment is crucial as outliers heavily influence statistics and model results.

## Question 8
**Which of the following are considered effective data cleaning techniques?**

Group of answer choices:
- Removing duplicate records to ensure data uniqueness.
- Normalizing text data to a standard case (e.g., all lowercase) for consistency.
- Handling missing values through imputation or removal.
- Increasing the dataset size artificially by duplicating existing records.
- Randomly shuffling data rows to break any pre-existing order.

**Correct Answer: A, B, C**

**Explanation:**
- Removing duplicate records ensures the dataset accurately represents unique observations.
- Normalizing text data ensures consistency and avoids mismatches during analysis.
- Handling missing values is essential to maintain data quality and prevent biases.
- Artificially increasing dataset size by duplicating records introduces bias.
- Randomly shuffling data rows does not constitute data cleaning.

## Question 9
**Which of the following statements describe advanced imputation techniques accurately?**

Group of answer choices:
- Mode Imputation - Always the preferred method for handling missing categorical data due to its simplicity.
- Deep Learning Imputation - Utilizing neural networks to predict missing values based on the patterns learned from the data.
- Principal Component Analysis (PCA) Imputation - Estimating missing values by reducing the dimensionality of the data.
- Multivariate Imputation by Chained Equations (MICE) - Imputing missing values by modeling each feature with missing values as a function of other features in a round-robin fashion.
- Time Series Imputation - Using methods like forward fill or linear interpolation to estimate missing values in time-ordered data.

**Correct Answer: B, D, E**

**Explanation:**
- Mode imputation is simple but not always preferred for categorical data.
- Deep learning utilizes neural networks to model relationships and predict missing values.
- PCA is primarily for dimensionality reduction, not imputation.
- MICE imputes values by modeling each incomplete feature as a function of other features.
- Time series imputation techniques are specifically designed for time-ordered data.

## Question 10
**Which of the following statements accurately describe the use of regression analysis in hypothesis testing?**

Group of answer choices:
- It can test hypotheses about the relationship between variables.
- It can include multiple independent variables to assess their impact on a dependent variable.
- Regression analysis can be used to predict the value of a dependent variable based on the value of at least one independent variable.
- Regression analysis is only applicable for linear relationships between variables.
- It always requires that data be normally distributed.

**Correct Answer: A, B, C**

**Explanation:**
- Regression can test hypotheses about variable relationships.
- Multiple regression can incorporate multiple independent variables.
- Regression predicts dependent variables using independent variables.
- Regression is not limited to linear relationships; non-linear regression exists.
- Data does not always need to be normally distributed; many regression methods are robust.

## Question 11
**Which of the following statements accurately describe different imputation techniques for handling missing data?**

Group of answer choices:
- Regression imputation uses a deterministic model to estimate missing values based on the relationships observed in other variables within the dataset, often leading to an underestimate of the true variability.
- Multiple imputation involves generating multiple different plausible values for missing data, each representing a possible scenario under which the data could be missing, and then using these varied datasets for further analysis.
- K-nearest neighbors (KNN) imputation replaces missing data based on the similarity of instances that are nearest in the feature space, which considers the entire set of available features to find the closest match.
- Using a random value from the dataset to fill in missing values can introduce additional variance to the data, which is generally undesirable.
- Mean imputation involves replacing missing values in a variable with the mean value of that variable calculated from available data.

**Correct Answer: A, B, C, E**

**Explanation:**
- Regression imputation uses relationships between variables but underrepresents variability.
- Multiple imputation creates several imputed datasets to model uncertainty.
- KNN imputation uses similarity of instances in feature space.
- Random value imputation introduces inconsistencies and uncontrolled variance.
- Mean imputation replaces missing values with the mean of available data.

## Question 12
**You are working on a dataset with customer transaction records and want to improve the model's ability to predict customer churn. Which of the following feature engineering strategies would likely enhance the predictive power of your model?**

Group of answer choices:
- Adding a feature that represents the frequency of transactions, grouped by month.
- Encoding the categorical variable "Membership Type" (e.g., Gold, Silver, Bronze) using one-hot encoding.
- Removing all categorical variables since they cannot directly contribute to predictions in numerical models.
- Creating a feature that calculates the average time between a customer's transactions.
- Creating a feature that represents the total monetary value of transactions for each customer over the last year.

**Correct Answer: A, B, D, E**

**Explanation:**
- Transaction frequency reveals trends in customer activity.
- One-hot encoding preserves categorical data without implying hierarchy.
- Categorical variables are valuable and should be properly encoded, not removed.
- Average time between transactions highlights patterns that may indicate churn risk.
- Total monetary value indicates customer engagement and spending behavior.

## Question 13
**Which features are present in the Hans Rosling visualization?**

Group of answer choices:
- It uses color to represent the country's income per capita.
- It uses histograms to show how the country's GDP has changed over time.
- It uses bubbles to represent the size of each country's population.
- It shows data for multiple countries over time.

**Correct Answer: C, D**

**Explanation:**
- It does NOT use color to represent income per capita; color typically differentiates regions.
- It does NOT use histograms; it uses bubble plots to show relationships.
- It DOES use bubbles to represent population size.
- It DOES show data for multiple countries over time.

## Question 14
**For dimensionality reduction, which of the following statements about PCA (Principal Component Analysis) are correct?**

Group of answer choices:
- PCA assumes that the data is linearly separable.
- PCA retains all original features but adjusts their scales.
- PCA reduces dimensionality by projecting data onto orthogonal components.
- PCA is sensitive to the scale of features and may require standardization beforehand.
- PCA components are ordered by the amount of variance they explain.

**Correct Answer: C, D, E**

**Explanation:**
- PCA doesn't assume data is linearly separable.
- PCA replaces original features with principal components.
- PCA projects data onto orthogonal components, reducing dimensionality.
- PCA is sensitive to feature scales and often requires standardization.
- PCA components are ordered by decreasing variance explained.

## Question 15
**Which of the following are true about the Euclidean distance metric?**

Group of answer choices:
- It can be used effectively for categorical data without any transformation.
- Squaring the differences between coordinates makes it more robust to outliers.
- It is sensitive to the scale of the data.
- Euclidean distance requires all features to be numeric.
- It measures the straight-line distance between two points in n-dimensional space.

**Correct Answer: C, D, E**

**Explanation:**
- Categorical data must be converted to numerical format before using Euclidean distance.
- Squaring increases sensitivity to large differences, making it less robust to outliers.
- Euclidean distance is sensitive to data scale.
- All features must be numeric for Euclidean distance calculation.
- It measures straight-line distance between points in n-dimensional space.

## Question 16
**Which of the following scenarios are well-suited for applying regularization techniques?**

Group of answer choices:
- Multicollinearity in the predictors.
- Low-dimensional datasets with no noise.
- High-dimensional datasets where the number of features exceeds the number of observations.
- Sparse datasets with many irrelevant features.
- When the goal is to maximize interpretability and sparsity in the model.

**Correct Answer: A, C, D, E**

**Explanation:**
- Regularization helps with multicollinearity by reducing coefficient variance.
- Low-dimensional, noise-free datasets don't typically need regularization.
- High-dimensional datasets benefit from regularization to control complexity.
- Regularization techniques like Lasso eliminate irrelevant features in sparse datasets.
- Techniques like Lasso promote sparsity and improve interpretability.

## Question 17
**Which of the following correctly interprets the limitations of a confusion matrix in evaluating a classification model?**

Group of answer choices:
- Metrics derived from the confusion matrix (e.g., recall, precision) do not reflect model calibration.
- A confusion matrix provides no insight into how well the model performs on imbalanced datasets.
- It directly measures the model's ability to distinguish between true positives and true negatives.
- It cannot capture probabilistic predictions but only hard classifications.
- A confusion matrix cannot be used to evaluate multi-class classification problems.

**Correct Answer: A, D**

**Explanation:**
- Confusion matrix metrics don't reflect calibration of predicted probabilities.
- Metrics from confusion matrices can provide insights for imbalanced datasets.
- Confusion matrices don't directly measure discrimination ability.
- Confusion matrices evaluate classification outcomes based on thresholds, not probabilities.
- Confusion matrices can be adapted for multi-class problems.

## Question 18
**Which of the following statements about bootstrapping are correct?**

Group of answer choices:
- The bootstrap method can be used to estimate confidence intervals for any statistic.
- Bootstrapping requires a minimum sample size of 100 to provide reliable results.
- Bootstrapping involves sampling with replacement from the original dataset.
- Bootstrapping assumes that the sample is representative of the population.
- Bootstrapping always produces unbiased estimates of the population parameters.

**Correct Answer: A, C, D**

**Explanation:**
- Bootstrapping can estimate confidence intervals for many statistics.
- Bootstrapping works with smaller sample sizes, though larger samples are more reliable.
- Bootstrapping involves sampling with replacement from the original dataset.
- Bootstrapping assumes the sample represents the population.
- Bootstrapping doesn't guarantee unbiased estimates.

## Question 19
**Which statements accurately describe the visualization?**

Group of answer choices:
- The relationship between the two variables is perfectly linear, as suggested by the points clustering tightly around the regression line.
- The scatterplot indicates a causal relationship between income and Metro Health Index.
- There is a positive linear correlation between income and the Metro Health Index.
- Outliers are present in the dataset, particularly at the higher end of the Metro Health Index.
- The fitted regression line suggests that increases in income are associated with higher values of the Metro Health Index.

**Correct Answer: C, D, E**

**Explanation:**
- The relationship is not perfectly linear; points are scattered around the regression line.
- Correlation doesn't imply causation; the scatterplot shows association, not causation.
- There is a positive linear correlation between the variables.
- Outliers are visible, especially at the higher end of the Metro Health Index.
- The upward regression line shows income increases are associated with higher health index values.

## Question 20
**You are working with a time-series dataset to predict energy consumption. The dataset includes timestamps, energy usage, and weather data. Which of the following feature engineering steps would enhance your model's ability to predict energy usage?**

Group of answer choices:
- Calculating a rolling average of energy consumption over a 7-day window.
- Combining temperature and humidity into a single feature using a formula like the heat index.
- Dropping the timestamp column entirely, as it is not directly useful for predictions.
- Extracting features like "Hour of Day," "Day of Week," and "Season" from the timestamp.
- Creating lag features, such as energy consumption values from the previous hour or day.

**Correct Answer: A, B, D, E**

**Explanation:**
- Rolling averages smooth fluctuations and highlight trends.
- Heat index combines related variables into more predictive features.
- Timestamps are essential for extracting time-based features.
- Temporal features provide context for time-dependent patterns.
- Lag features capture the influence of past values on current consumption.

## Question 21
**Which statements about the density plot are accurate?**

Group of answer choices:
- Both airlines have a majority of flights with negative delay times (arriving early).
- The shaded overlap area represents flights with similar delay distributions between the two airlines.
- The peak density of United Air Lines Inc.'s arrival delays occurs closer to 0 compared to Alaska Airlines Inc.
- United Air Lines Inc. has a higher proportion of flights with delays greater than 50 minutes compared to Alaska Airlines Inc.
- Alaska Airlines Inc. has a smaller variance in arrival delays compared to United Air Lines Inc.

**Correct Answer: B, C, E**

**Explanation:**
- Most flights are on time or slightly delayed, rather than arriving early.
- The overlapping regions represent similar delay distributions between airlines.
- United's peak density is closer to 0, showing more on-time flights.
- Alaska Airlines has more flights with delays exceeding 50 minutes than United.
- Alaska Airlines' curve is narrower and more peaked, reflecting smaller variance.

## Question 22
**Which of the following statements correctly adhere to the Principles of Effective Visualization?**

Group of answer choices:
- Including a descriptive title in a visualization is unnecessary if the axes are labeled correctly.
- Tailoring visualizations to the audience's knowledge level ensures the data is communicated effectively.
- Minimizing chart elements like gridlines, decorations, and excessive colors ensures simplicity and reduces cognitive load.
- Adding 3D effects to bar charts improves the interpretation of data and is a recommended practice.
- Using redundant encoding, such as both color and shape, enhances clarity and supports accessibility.

**Correct Answer: B, C, E**

**Explanation:**
- Descriptive titles are essential even with labeled axes.
- Tailoring to audience knowledge level improves communication effectiveness.
- Minimizing chart elements reduces cognitive load and improves focus.
- 3D effects distort perception and reduce accuracy.
- Redundant encoding improves accessibility and clarity.

## Question 23
**Which statements about normal distributions and box plots are correct?**

Group of answer choices:
- The median in the box plot corresponds to the peak of the normal distribution curve.
- The tails of the normal distribution correspond to the outliers beyond the whiskers in a box plot.
- The length of the box in a box plot increases as the variability of the middle 50% of the data increases.
- In a perfectly normal distribution, there are no outliers beyond the whiskers in the box plot.
- In a normal distribution, approximately 24.65% of the data lies between the first quartile (Q1) and the median.

**Correct Answer: A, C, E**

**Explanation:**
- In a normal distribution, the median aligns with the peak of the curve.
- The box length (IQR) increases with greater variability in the middle 50%.
- The tails do correspond to potential outliers in box plots.
- Even in normal distributions, outliers can exist beyond the whiskers.
- In a normal distribution, exactly 25% of data lies between Q1 and the median.
