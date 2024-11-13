# Laundry Room User Count Prediction

This project aims to predict the number of users in a laundry room during a given time period based on factors like time of day, weather, and holidays. The project includes data preprocessing, exploratory data analysis, model building, and evaluation to provide insights and predictions for user count in a laundry facility.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Visualizations](#visualizations)
- [Presentation](#presentation)
- [Contributing](#contributing)

## Project Overview
The project steps include:
1. **Data Cleaning and Preprocessing**: Handling missing values, encoding categorical features, and scaling.
2. **Data Analysis**: Aggregating and visualizing data to identify patterns in laundry room usage.
3. **Model Building and Evaluation**: Training a machine learning model (Linear Regression) to predict user counts.
4. **Visualization**: Generating insights through charts to understand user behavior.

The project is fully contained within a single Jupyter Notebook file, with an accompanying PowerPoint presentation.

## Dataset
The dataset (`enhanced_washing_room.csv`) includes:
- `Time Slot`: Time of day (e.g., morning, afternoon, evening, night)
- `Weather`: Weather conditions during the period
- `Holiday`: Indicator of whether the day is a holiday
- `User Count`: Number of users (target variable)

> Note: The column `Cycle Duration` is excluded from the analysis.

## Installation
To run this notebook, clone the repository and install the required libraries:

## Project Workflow
The workflow in the notebook includes:

Data Preprocessing: Dropping missing values, removing duplicates, encoding categorical data, and scaling features.
Exploratory Data Analysis (EDA): Aggregating and visualizing user count by time slot, weather, and holidays.
Model Selection: A Linear Regression model was chosen due to its interpretability and efficiency on small datasets.
Model Evaluation: The model’s performance is evaluated using R² and Mean Squared Error (MSE) to assess prediction accuracy.

## Results
The Linear Regression model achieved:

- R² Score: ~0.79
- Mean Squared Error (MSE): ~6.00
These metrics indicate that the model captures key patterns in user behavior, though further improvements could be made by testing more complex models.

## Visualizations
Key visualizations included in the notebook:

User Count by Time Slot: Shows peak times of usage in the laundry room.
Effect of Weather and Holidays: Examines how external conditions influence user count.
Example Code for Visualization

## Presentation
The project includes a PowerPoint presentation (DS.pptx) that provides an overview of:

- Project objectives and motivation
- Data analysis and preprocessing steps
- Model selection and evaluation metrics
- Key findings and visualizations
You can download the presentation for a high-level summary of the project and insights.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

```bash
git clone https://github.com/akshith120/Laundry-Room-Analysis.git
cd laundry-room-user-count-prediction
pip install -r requirements.txt
