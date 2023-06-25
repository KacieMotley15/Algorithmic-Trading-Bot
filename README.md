# Project Title

Stock Market Prediction using Support Vector Machines (SVM) and Moving Averages

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results and Impact Analysis](#results-and-impact-analysis)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project aims to predict stock market trends using Support Vector Machines (SVM) and Moving Averages. It utilizes historical stock price data, calculates the moving averages, applies SVM for prediction, and evaluates the strategy's performance.

## Installation
1. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Prepare the data:
   - Ensure you have historical stock price data in CSV format.
   - Modify the `data_path` variable to point to your data file.
   - Adjust the parameters `sma_short_window` and `sma_long_window` in `main.py` to define the moving average windows.

2. Run the program:
   - The program will perform SVM-based stock market prediction using the specified moving average windows and display the results.

## Results and Impact Analysis

The program will generate a plot comparing the actual returns with the strategy returns based on the SVM predictions and moving averages. By analyzing this plot, you can assess the impact of changing the moving average windows and the SVM model on the strategy's performance.

For example:
- Increasing the SMA windows might provide smoother predictions but could result in delayed responses to market changes.
- Decreasing the SMA windows might yield more responsive predictions but could increase the noise in the predictions.

By experimenting with different SMA windows and SVM models, you can optimize the strategy's performance based on your specific objectives and trading style.

## Contributing

Contributions to this project are welcome. To contribute, please follow these guidelines:
- Fork the repository and create a new branch for your contribution.
- Make your changes and submit a pull request, explaining the purpose and scope of your contribution.
- Adhere to the project's coding style and conventions.
- Address any feedback or comments received during the review process.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries about this project, please contact [Your Name](mailto:your-email@example.com).
