# Traffic Flow Prediction Using Deep Learning

This project compares three deep learning models—Stacked LSTM, Stacked GRU, and Hybrid CNN LSTM—for forecasting hourly traffic volume using the PeMS03 dataset.

## Files

- `Deep_Learning_Project_08.ipynb` - Notebook for 8-hour lookback window
- `Deep_Learning_Project_12.ipynb` - Notebook for 12-hour lookback window (baseline)
- `Deep_Learning_Project_16.ipynb` - Notebook for 16-hour lookback window
- `Deep_Learning_Project_24.ipynb` - Notebook for 24-hour lookback window
- `pems03.csv` - Dataset containing hourly traffic data from 151 sensors (2002–2024). Download from [Caltrans PeMS](https://pems.dot.ca.gov/) (registration required)
- `Traffic-Volume-Forecasting-Using-Deep-Learning.pdf` - Detailed analysis, methodology, and results

## How to Run

1. Upload the dataset and desired notebook to [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. Each notebook is self-contained and independent

## Results

The Hybrid CNN LVM model achieved the highest accuracy (MAE: 245.88 with 16-hour window), while the Stacked GRU trained the fastest (183 seconds), highlighting the trade-off between precision and efficiency.
