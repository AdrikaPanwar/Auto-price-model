# Auto-price-model

## Overview

This repository contains a model for predicting automobile prices using Azure Machine Learning Studio. The model leverages real-time predictions and various Azure ML tools to analyze and forecast vehicle prices.

You can view the model and its real-time predictions through the following Azure ML Studio link:

[Azure ML Studio Prediction Model](https://ml.azure.com/experiments/id/69278a1e-a7df-4958-8246-6f01e654617f/runs/791d89e7-8996-4e61-b571-61a0a4758dc2?wsid=/subscriptions/81b9c30e-6a4e-473c-b832-9e7e63fba7dd/resourceGroups/prismat/providers/Microsoft.MachineLearningServices/workspaces/arika&tid=f1f5b0b6-4e0a-4467-b487-5f0ccab4e798#/?graphId=f4bb0bd3-8c53-428d-a06b-9f551799f42c&label=Predict+Auto+Price&path=%2Fexperiments%2Fid%2F69278a1e-a7df-4958-8246-6f01e654617f%2Fruns%2F791d89e7-8996-4e61-b571-61a0a4758dc2&runId=791d89e7-8996-4e61-b571-61a0a4758dc2)

## Project Pipeline

Below is a visual representation of the model pipeline:

![Pipeline Model](https://github.com/AdrikaPanwar/Auto-price-model/assets/162022172/dbe07cd6-d3ab-4ebe-9f99-fdc1a6b5eafd)

## Step-by-Step Guide

1. **Create a Resource Group**: In the Azure portal, click on the three horizontal lines, navigate to "Resource Groups," and click "Create" to set up a new resource group.
2. **Open Azure ML Studio**: Access the workspace within your resource group.
3. **Design Your Pipeline**: Use the Designer in Azure ML Studio to create your pipeline. Drag and drop components to build your workflow.
4. **Use Sample Data**: Create pipelines using sample data or manually download relevant datasets (e.g., weather, automobile, health) from the web.
5. **Filter and Deploy**: Configure the pipeline to apply filters and deploy it. Check visualizations to ensure the pipeline is working as expected.

![Visualizations](https://github.com/AdrikaPanwar/Auto-price-model/assets/162022172/a9c142a4-a3d0-41b9-9d06-31650a49298c)

## Data Analysis

I utilized the Data Wrangler tool within Microsoft Fabric to perform statistical summaries and visual analysis of the data.

## Notes

I am using an Azure free subscription for this project, which limits certain functionalities. Due to these constraints, I cannot directly deploy the model here. However, the experience with Data Wrangler, regression, MLflow, hyperparameters, and model retraining has been highly educational.

I encourage you to explore these tools and techniques as hands-on experience is invaluable for gaining true knowledge.


