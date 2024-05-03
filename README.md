

# Stock Price Predictor

## Overview
This project aims to predict stock prices using historical stock data and machine learning techniques. It utilizes linear regression to model the relationship between stock features (such as Open, High, Low, and Volume) and the closing price of stocks.

## Author
Shreyas Natarajan

## Requirements
- Python 3
- Libraries: pandas, numpy, scikit-learn, matplotlib

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/shreyasnat2804/stock-price-predictor.git
   cd stock-price-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the stock data:
   - Obtain historical stock data in CSV format.
   - Place the CSV files in the `data/Stocks` directory.

## Usage

### Using Google Colab
This project can be easily utilized in Google Colab, a cloud-based platform for running Python notebooks. Follow these steps to use the project in Google Colab:

1. Open Google Colab ([colab.research.google.com](https://colab.research.google.com/)).

2. Click on "File" in the menu and select "Upload notebook".

3. Upload the `predict_stocks.ipynb` notebook file from this project.

4. Upload the stock data file (`data.zip`) to your Google Drive:

   - Download the stock data file from [this link](https://drive.google.com/file/d/1VPIWaFtFvtPRGEkxv0nZD0wmuonjYk7i/view).
   
   - Upload the downloaded file to your Google Drive.
   
   - Place the `data.zip` file in the same folder as the uploaded `predict_stocks.ipynb` notebook file.

5. Follow the instructions within the notebook to execute the code cells.

6. If necessary, mount Google Drive in the notebook to access the uploaded data.

7. Execute the code cells sequentially, following the provided documentation and instructions.


## Acknowledgements
- [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
- [scikit-learn](https://scikit-learn.org/) for machine learning tools.
- [Matplotlib](https://matplotlib.org/) for data visualization.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

