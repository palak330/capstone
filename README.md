# capstone
Are there unit tests for the API?

Yes, unit tests for the API should be created to ensure that it behaves as expected and handles edge cases.

Are there unit tests for the model?

Yes, unit tests for the model can be created to validate that the model training and inference functions perform correctly, including verifying that the model handles inputs as expected.

Are there unit tests for the logging?

Yes, unit tests for logging can ensure that logs are correctly written and contain expected information, which helps in monitoring and debugging.

Can all of the unit tests be run with a single script and do all of the unit tests pass?

Ideally, yes, unit tests should be runnable with a single script or command, such as through a test suite, and all tests should pass to confirm that the system is functioning as intended.

Is there a mechanism to monitor performance?

Yes, a mechanism to monitor performance, such as performance metrics tracking or drift detection, is important to ensure that the model continues to perform well over time.

Was there an attempt to isolate the read/write unit tests from production models and logs?

Yes, isolating read/write unit tests from production models and logs is a best practice to ensure that testing does not affect production data or operations.

Does the API work as expected? For example, can you get predictions for a specific country as well as for all countries combined?

Yes, the API should be tested to ensure that it provides predictions for specific countries as well as aggregate predictions if required.

Does the data ingestion exist as a function or script to facilitate automation?

Yes, data ingestion should be automated through functions or scripts to streamline the process of data collection and preprocessing.

Were multiple models compared?

Yes, comparing multiple models helps in selecting the best-performing model based on evaluation metrics.

Did the EDA investigation use visualizations?

Yes, Exploratory Data Analysis (EDA) should use visualizations to help understand data distributions, patterns, and relationships.

Is everything containerized within a working Docker image?

Yes, containerizing the application and its dependencies within a Docker image ensures consistency across different environments and simplifies deployment.

Did they use a visualization to compare their model to the baseline model?

Yes, visualizations comparing the performance of the model to a baseline model can help in understanding improvements and making informed decisions.
