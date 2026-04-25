# Autonomous Greenhouse — Smart Climate Control & Irrigation System

This project uses artificial intelligence and IoT data analysis to automate greenhouse management. It relies on a neural network that predicts and controls several components:

- **Irrigation**: pump activation based on humidity levels
- **Ventilation**: fan management for cooling or heating
- **Peltier system**: activation when temperature is too high
- **Heating mat**: activation when temperature is too low
- **Lighting**: control based on time of day

## Tech Stack

- **Python** — data manipulation and visualization
- **Pandas, NumPy, Seaborn** — data analysis and preprocessing
- **Scikit-learn** — normalization and train/test split
- **TensorFlow / Keras** — neural network for classification
- **Matplotlib** — results visualization

## Dataset

The data used in this project comes from the [IoT Agriculture 2024](https://www.kaggle.com/datasets/wisam1985/iot-agriculture-2024/data) dataset on Kaggle.

The file `IoTProcessed_Data.csv` was downloaded from this source and used for analysis and model training.
