# Insider Threat Detection — Anomaly Detection

## Overview

This project explores whether machine learning can identify unusual user activity in a simulated healthcare environment.

The project uses Isolation Forest, an unsupervised machine learning method, to identify activity that is different from the main pattern in the data.

The dataset is simulated and does not contain real patient information.

## Features

The project looks at example user activity such as:

- Login time
- Download volume
- Device
- Location

## Machine Learning Model

Isolation Forest is used to identify unusual activity without using a predefined normal/suspicious label for the model.

## Technologies

- Python
- Pandas
- Scikit-learn
- Google Colab

## Example Observation

In the simulated dataset, the model identifies several records with unusual combinations of activity as anomalies.

This demonstrates the basic idea of anomaly detection.

## Limitations

This is a small proof-of-concept project using simulated data.

The results should not be interpreted as evidence that the model can reliably detect real insider threats.

A larger and more realistic dataset would be needed for proper evaluation.

## Future Work

Possible future work could include:

- Larger datasets
- Comparison of different anomaly detection methods
- More user behaviour features
- More realistic healthcare access scenarios
- Evaluation using suitable security datasets
