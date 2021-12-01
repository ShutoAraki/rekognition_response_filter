# Amazon Rekognition Custom Labels response analysis

Looking at the result table for your Amazon Rekognition Custom Labels model, have you wondered "Can't I control the assumed thresholds so that I can figure out the model performance based on a custom metric?"

This Jupyter Notebook walks you through how to analyze DetectCustomLabels API responses from your testing dataset.


## Prerequisites

- `AmazonRekognitionCustomLabelsFullAccess` is attached on the IAM role on your environment
- Download the `testing_manifest_with_validation.json` file from the Rekognition Custom Labels management console and place it on the same directory as this README.md.