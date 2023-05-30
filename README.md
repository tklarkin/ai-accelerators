**DataRobot [AI Accelerators](https://www.datarobot.com/aiaccelerators/) are repeatable, code-first workflows designed to help speed up model development, deployment and time to value using the [DataRobot API](https://datarobot-public-api-client.readthedocs-hosted.com/en/latest-release/).**

[Install the DataRobot Python Client Package](https://pypi.org/project/datarobot/).  
<a href="https://pypi.org/project/datarobot/"><img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/upgini"></a>
<a href="https://pypi.org/project/datarobot/"><img alt="PyPI" src="https://img.shields.io/pypi/v/upgini?label=Release"></a>
<a href="https://pypistats.org/packages/datarobot"><img alt="Downloads from pypistats" src="https://pepy.tech/badge/upgini"></a>


## 🚀 Getting started

1. Clone this repo
2. Import the desired accelerator into your preferred notebook (e.g., jupyter, Kaggle, Databricks Notebooks, Google Colab). We recommend using [DR-Notebooks](https://www.datarobot.com/platform/notebooks/).
3. Execute the notebook. 
4. Learn and understand the accelerator content. 
4. You should now be able to modify the accelerator to solve your own problem. The easiest place to start is to replace the input data with your own. 

## ❔Support
Please report feedback and problems by opening a Github Issue in this repo.
Please note: The code in these repos is sourced from the DataRobot user community and is not owned or maintained by DataRobot, Inc. You may need to make edits or updates for this code to function properly in your environment.

## 🤔 Finding the Accelerator you need
| Title | Accelerator Topic | What it's good for | 3rd Party Integration | Extensibility to other Integrations |
|---|---|---|---|---|
| [Automated Feature Discovery with Multiple Tables](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/Azure_End_to_End.ipynb) | Automated Feature Discovery workflow | Repeatable end-to-end AFD workflow in Snowflake from data to batch predictions | Snowflake | Horizontal approach that applies to classification/ regression problems with a time-component |
| [Azure Storage End-to-End Workflow with DataRobot](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/Azure_End_to_End.ipynb) | Azure End-to-End | Repeatable end-to-end workflow in Azure from data to batch predictions | Azure | Low, Azure focused |
| [Creating Custom Blueprints with Composable ML](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/custom_blueprints) | Create custom blueprints | Learn how to create custom blueprints | - | High, advanced use of DataRobot API |
| [Customizing Lift Charts](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/customizing_lift_charts) | Custom lift charts | Learn how to create a custom lift chart | - | High, advanced use of DataRobot API |
| [Deploying a DataRobot model into AWS SageMaker](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/sagemaker_deployment) | AWS SageMaker | Build an AI/ML model within DataRobot which will then be deployed and hosted within AWS SageMaker | AWS | Low, AWS focused |
| [End-to-end demand forecasting and retraining workflow](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/Demand_forecasting_retraining/End_to_end_demand_forecasting_retraining.ipynb) | Workflow for setting up retraining for time series, and executing it when model degrades | Repeatable workflow for setting up retraining. Talks through nuances of tracking actuals in TS, failed models, and performance after retraining | Snowflake | High, time-series focused, could easily swap Snowflake for another data source |
| [End-to-end Time Series Cold Start Demand Forecasting](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/Demand_forecasting_cold_start) | Time series Demand Forecasting (cold start) | Timeseries (cold start) workflow.  Incomplete history for series and new series are very common in TS.  This is a playbook for handling these challenges. Follows the  | Snowflake | High, generalizes to all multi-series problems. Can use other data source/destination |
| [End-to-end Time Series Demand Forecasting Workflow](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/End_to_end_demand_forecasting) | Time series Demand Forecasting | This is a template for any time series project with the API. Precursor to cold-start notebook | Snowflake | High, easily can swap out Snowflake for another datasource.  |
| [End-to-end workflow with DataRobot and Snowflake](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/Snowflake_End_to_End) | Snowflake End-to-End | Repeatable end-to-end workflow in Snowflake from data to batch predictions | Snowflake | Low, Snowflake focused |
| [End-to-End workflows with DataRobot and AWS (S3 and Athena)](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/AWS_End_to_End) | AWS End-to-End | Repeatable end-to-end workflow in AWS from data to batch predictions | AWS | Low, AWS focused |
| [End-to-end workflows with DataRobot and Databricks](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/Databricks_End_To_End.ipynb) | DBX End-to-End | Repeatable end-to-end workflow in DBX from data to batch predictions | Databricks | Low, DBX focused |
| [Feature Reduction with FIRE](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/feature_reduction_with_fire) | Feature Selection with FIRE | Learn how to use FIRE for feature selection | - | High, advanced use of DataRobot API |
| [Google Cloud Platform & BigQuery: End-to-end AI/ML modeling](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/GCP%20DataRobot%20End%20To%20End.ipynb) | GCP End-to-End | Repeatable end-to-end workflow in GCP from data to batch predictions | GCP | Low, GCP focused |
| [Gramian Angular Fields and High Frequency Data](https://github.com/datarobot-community/ai-accelerators/tree/main/game-changer/high_freq_data_to_images) | Apply visualAI on high frequency data | Learn how to use Gramian Angular Fields to generate features from high frequency time series datasets like sensor readings | - | High, horizontal use case approach |
| [How to Move a Model](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/model_migration) | Model Migration | Sample code to move a model between clusters | - | High, advanced use of DataRobot API |
| [Hyperparameter Optimization and Gridsearch via Python API](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/Hyperparameter_Optimization) | Hyperparameter tuning | Learn how to use the API for hyperparameter tuning | - | High, advanced use of DataRobot API |
| [Leveraging Hyperscaler API for Efficient Data Enrichment](https://github.com/datarobot-community/ai-accelerators/blob/main/advanced-experimentation/gcp_sentiment/GCP_enrich_sentiment.ipynb) | Enriching training data with GCP APIs for NLP (sentiment, etc) | Extensible workflow to add new features for text, but the structure extends to the Vision API, etc | GCP | High, could apply to Azure/ AWS, other GCP APIs |
| [Model Fine-Tuning with Eureqa](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/fine_tuning_with_eureqa) | Fine tune Eureqa blueprints | Learn how to fine tune Eureqa blueprints via the API | - | High, advanced use of DataRobot API |
| [Model Selection via Custom Metrics](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/GCP%20DataRobot%20End%20To%20End.ipynb) | Custom metrics | Learn how to rank models with custom metrics | - | High, advanced use of DataRobot API |
| [Monitoring AWS Sagemaker models with DataRobot MLOps](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/monitor_sagemaker_model_in_DataRobot) | Train and host a Sagemaker model that can be monitored in DR ML Ops | Repeatable workflow for applying ML Ops to Sagemaker models, building DataRobot compatible Sagemaker containers to host, train, and monitor models | AWS | Low, AWS focused, but broadly applies to Sagemaker deployments |
| [Multi-model Analysis](https://github.com/datarobot-community/ai-accelerators/blob/main/advanced-experimentation/multi_model_analysis/Multi-Model%20Analysis.ipynb) | Easily compare insights from models across different projects | Feature impact, model error, and partial dependence from models across N projects, for easy comparison. Inspired from our internal churn models | - | High, DR / Matplotlib/Seaborn focused |
| [Native integration DataRobot and Snowflake Snowpark](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/snowflake_snowpark/Native%20integration%20DataRobot%20and%20Snowflake%20Snowpark-Maximizing%20the%20Data%20Cloud.ipynb) | Use Snowpark for feature eng, and deploy/monitor a PPS in Snowflake with ML Ops | Snowpark integration, Java scoring code deployment with PPS in Snowflake | Snowflake | Low, Snowflake focused |
| [Prepare & Leverage Image Data for DataRobot with Databricks](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/image_data_databricks) | Image data Databricks | Base64 conversion for images, project creation, and scoring pipeline | Databricks | High, broadly applicable to computer vision |
| [Present Datarobot prediction insights with Streamlit](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/Churn_app_Streamlit) | Streamlit prediction insights app | Streamlit prediction insights app that can be easily customized, helps transform prediction explanations | Streamlit | High, Streamlit baseline template |
| [Recommendation Engine with DataRobot's MultiLabel](https://github.com/datarobot-community/ai-accelerators/tree/main/game-changer/Recommendation%20Engine) | Multilabel recommendation engine | Learn how to create a recommendation engine that combines multilabel and AFD | - | High, horizontal use case approach |
| [Retail - Predict Factory Quantities for New Products](https://github.com/datarobot-community/ai-accelerators/blob/main/advanced-experimentation/Retail_Industry_Predicting_Factory_Orders_New_Products/Retail%20Industry%20-%20Predicting%20Factory%20Order%20Quantities%20for%20New%20Products.ipynb) | Predicting demand for new products with very limited (annual) data. Regression, not TS | Multimodal, base64 conversion, detailed EDA and business rule analysis | - | High, horizontal use case approach |
| [Spectrograms and Numerics for High Frequency Classification](https://github.com/datarobot-community/ai-accelerators/blob/main/game-changer/high_freq_data_to_images/high_frequency_data_classification_using_spectrograms_n_numerics/high_frequency_classification_spectrograms_n_numerics.ipynb) | Advanced Feature Eng. and Visual AI with Acoustic Data | Converting audio or high frequency sensor data into visual features and numeric features for analysis. Extends to machine failures, sensor readings, EM signals in general | - | High, horizontal use case approach |
| [Tackling Churn with ML - Before Modelling](https://github.com/datarobot-community/ai-accelerators/tree/main/game-changer/churn_blog) | Churn with ML | Teach the problem framing and data management steps required before modeling begins | - | High, horizontal use case approach |
| [Time Series Demand Forecasting What-If App](https://github.com/datarobot-community/ai-accelerators/tree/main/end-to-end/Demand_forecasting_what_if_app) | What-if-app for timeseries demand forecasting | Streamlit what-if app for timeseries demand forecasting | Streamlit | High, horizontal use case approach |
| [Use MLFlow with DataRobot API for tracking experimentation](https://github.com/datarobot-community/ai-accelerators/tree/main/advanced-experimentation/MLFLOW) | Repeatable experiments, meta-data tracking | Repeatable experiments that use MLflow to track key metrics across experiments e.g. model factories with multiple project settings, feature derivation windows | MLFlow | High |
| [End-to-end workflow with DataRobot and SAP Hana](https://github.com/datarobot-community/ai-accelerators/blob/main/end-to-end/SAP_End_to_End/SAP_End_to_End.ipynb) | SAP End-to-End | Repeatable end-to-end workflow in SAP from data to batch predictions. Includes building out SAP HANA environment | SAP | Low, SAP Focused |
| [The Self-Join Technique: Machine Learning with Panel Data](https://github.com/datarobot-community/ai-accelerators/blob/main/advanced-experimentation/SelfJoins/self-joins-panel-data.ipynb) | Advanced Feature Eng and Modeling with Panel data/ irregular time-series data | Repeatable workflow to use Automated Feature Discovery to derive time-based features by joining one table to itself multiple times on different panel dimensions. Highly useful in healthcare, manufacturing, B2B/B2C data...any data with repeat observations per subject | - | High - powerful, horizontal approach that applies to all industries |

## Links to YouTubue
Coming soon!
## Useful Links
Coming soon!
