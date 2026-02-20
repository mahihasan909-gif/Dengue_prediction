# Dengue Prediction

## Overview
The Dengue Prediction project aims to provide an efficient solution for predicting dengue outbreaks using machine learning algorithms and weather data. With the increasing frequency of dengue cases globally, this tool will assist in timely warnings and better management of health resources.

## Features
- Machine Learning Model for outbreak prediction
- User-friendly interface for inputting data
- Visualization of prediction results

## Project Structure
- `data/`: Contains datasets used for training and testing.
- `models/`: Contains serialized machine learning models.
- `notebooks/`: Jupyter notebooks for analysis and exploration.
- `src/`: Source code for the application.

## Requirements
- Python 3.6+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Flask (for web app)

## Installation
To install the dependencies, use the following command:
```bash
pip install -r requirements.txt
```

## Usage
To use the project, run the `app.py` file:
```bash
python app.py
```
Navigate to `http://localhost:5000` to access the web interface.

## Dataset
The datasets used for training and evaluating the model can be found in the `data/` directory. Ensure to preprocess the data before training.

## Results
The model's accuracy and other performance metrics will be displayed on the results page after running predictions.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions and enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.