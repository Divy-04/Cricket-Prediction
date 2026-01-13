# Cricket Win Prediction

A machine learning project to predict the outcome of cricket matches based on historical data and team performance metrics.

## Project Overview

This project uses machine learning algorithms to predict whether a cricket team will win or lose a match. The model is trained on historical cricket data including match details and deliveries information.

## Features

- **Data Analysis**: Comprehensive analysis of historical cricket match data
- **Feature Engineering**: Creating meaningful features from raw cricket statistics
- **Machine Learning Models**: Multiple ML algorithms trained and evaluated
- **Predictions**: Predict match outcomes based on team performance and conditions

## Project Structure

```
Cricket-prediction/
├── main.ipynb              # Main Jupyter notebook with analysis and models
├── deliveries.csv          # Ball-by-ball delivery data
├── matches.csv             # Match information and results
├── delivery_df.dtypes      # Data type information
└── README.md               # This file
```

## Dataset

- **matches.csv**: Contains match-level data including teams, date, venue, and winner
- **deliveries.csv**: Contains ball-by-ball delivery data including runs, wickets, and bowler/batsman info

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Divy-04/Cricket-prediction.git
cd Cricket-prediction
```

2. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook main.ipynb
```

## Usage

1. Open `main.ipynb` in Jupyter Notebook
2. Run all cells to perform data analysis and model training
3. The notebook will display visualizations and model performance metrics
4. Use the trained model to make predictions on new data

## Model Performance

The models are evaluated using various metrics including:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Future Improvements

- Include more advanced features like recent form, player injuries, weather conditions
- Implement deep learning models
- Create a web interface for predictions
- Add real-time data integration

## Author

Divy-04

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.
