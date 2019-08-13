# Build (automated) Machine Learning pipeline from an engineeringer perspective. 
### Requirement: Anaconda (Python 3.6)

### 1. An overview of Machine learning workflow, including data preprocessin & feature engineering, model selection and model optimization.  

### 2. Most popular Machine Learning models implementaions with Python.

### 3. Data Preprocessing and feature engineering examples.

### 4. Mmodel selection methods.

### 5. Model optimization (hyper-parameter tuning) methods.

### 6. (Automated) Machine Learning pipeline.

### 7. Deep Learning examples. 





# Data Science Project Standard Operation Process:

### Understand the whole picture of the scientific/business project focusing on goals, scope, resources, limitations, iterations and checkpoints
1. Get familiar with decision making processes and split them for different scenarios.
2. Identify human resource and data sources.
3. Make assumptions and validata them with data.
4. Be clear about tools & technologies to be used and final deliverables.
5. Be clear about evaluation metrics for modeling and outcomes.
6. Identify potential risks and faulures. 

### Understand the data to be used through the project
1. Clear about data access and authorization issues.
2. Load data into platform for initial analysis.
3. Sensitive information operations (deletion or changing critial values).
4. Identify data-sets to be used.
5. Identify data schema and fields descriptions.
6. Determine the quantity of each data-set and be clear about the discrepancies.
7. Explore sample data-set (count, mean, std, percentiles, distributions etc.)
8. Understand the data collection processes and potential errors. 
9. Study correlations and remember correlation does not imply causation.
10. Detect noise and outliers and treat them properly.
11. Ensure the sample data-set represents the population.
12. Perform data quality checks.
13. Split train & test data.

### Prepare the final data-set for modeling by joining different data sources, cleaning, formatting and feature engineering
1. Identify relevant data-sets for modeling.
2. Aggregate data in a proper way for final data-set.
3. Write functions/modules to have flexibility for cleaning/formatting/massaging data later in the project.
4. Treat outliers accordingly.
5. Apply feature engineering.
6. Select features by filter/wrapper/embedded methods.
7. Rank features by the importances.
8. Build data transformation pipelines.
9. Write custom transformers for specific operations in the profect.
10. Versioning data-sets with detailed comments.

### Modeling
1. Determine ML problem type (supervised/non-supervised/reinforcement).
2. Shortlist proper ML models.
3. Set-up evaluation metrics, especially for imbalance data-set.
4. Set-up tolerance level of false position and false negative.
5. Set-up cross validation.
6. Analyze most important features of performant models.
7. Analyze model sensitivities to each feature.
8. Fine-tune model hyperparamters.
9. Determine model workload for deployment (online, batch or streaming).
10. Perform computation complexity analysis on time.

### Evaluation each phase
1. Review the whole pipeline addressing all issues.
2. Presenting how outcomes meet objectives and explain the potential limitations and risks.

### Deployment for operation
1. Test in production.
2. Monitor the performance.
3. Identify strategies to improve the model (re-training, re-evaluation, de-deployment).

PS: always documenting the thinking processes.
