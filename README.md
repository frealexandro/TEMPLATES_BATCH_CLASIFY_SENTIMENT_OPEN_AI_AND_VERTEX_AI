# Machine Learning and Data Processing Notebooks

This repository contains three Python notebooks focused on machine learning, data processing, and API interactions with Google Cloud Platform and OpenAI.

## Notebook 1: Batch Prediction on Google AI Platform

This notebook contains a Python script designed to perform batch predictions on a machine learning model hosted on Google AI Platform. 

### Key Features:
- Utilizes Google Cloud Storage API and Google AI Platform API
- Efficiently uploads data and submits batch prediction jobs
- Processes input data using pandas and numpy
- Main function: `batch_prediction_job`
- Supporting classes: `Param` and `Input_Data`

The script takes important parameters such as project ID, location, model resource name, and input/output URIs, and returns a list of prediction result file names stored in Google Cloud Storage.

## Notebook 2: Social Media Data Classification using OpenAI GPT-3

This notebook processes and classifies social media data using the OpenAI GPT-3 model (`text-davinci-002`).

### Key Features:
- Connects to Google Cloud BigQuery for data retrieval
- Uses OpenAI's API for sentiment analysis and topic classification
- Processes data in batches
- Merges classification results back into the original dataset

### Workflow:
1. Dependency Installation
2. Google Cloud Configuration
3. Data Retrieval
4. Data Cleaning and Preparation
5. Sentiment and Topic Classification
6. Merging Results
7. Final Output Generation

The final output is a comprehensive dataset including the original data enriched with sentiment analysis and topic categorization for each social media post.

## Notebook 3: Enhanced Batch Prediction on Google AI Platform

This notebook performs a batch prediction job on Google AI Platform, similar to Notebook 1 but with additional features.

### Key Features:
- Uses Google Cloud Storage and AI Platform APIs
- Incorporates Pandas and Numpy for data processing
- Main function: `batch_prediction_job`
- Classes: `Param`, `Input_Data`, and `Data_Frame`

### Key Components:
- `batch_prediction_job`: Submits batch prediction jobs and retrieves results
- `Param`: Defines parameters for the prediction job
- `Input_Data`: Reads and prepares input data
- `Data_Frame`: Transforms input data and uploads to Google Cloud Storage

This notebook provides a more comprehensive approach to batch prediction, including data preparation and transformation steps.

## Getting Started

To use these notebooks, you'll need:
1. A Google Cloud Platform account with necessary APIs enabled
2. An OpenAI API key (for Notebook 2)
3. Python environment with required libraries installed

Please refer to each notebook for specific setup instructions and required dependencies.

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
