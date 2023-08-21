# Sales Forecasting with Prophet

This repository contains code and information about performing sales forecasting using the Prophet library. In this project, we analyze historical sales data of a retail store and use the Prophet library to predict future sales for specific products and brands.

## Project Overview

In this project, we aim to forecast future sales for a retail store using historical sales data. We use the Prophet library, which is an open-source forecasting tool developed by Facebook. The project includes data preprocessing, analysis, demand forecasting, and visualization of results.

## Setup
Example data is given in this [drive](https://drive.google.com/drive/folders/1BkMpaaI4hooJ41FINbRpgd9Gz9oSY6bz?ths=true)
Right click the folder ‘Forecast (Python)’ > Organize >  Add shortcut > select My Drive and add shortcut there

Now open Forecasting and analysis.ipynb’ (google colab notebook)
1. Change the base_path under the Setup block with the directory of wherever you saved the shortcut in your drive
2. Run Setup , allow permission to connect to drive
3. Run Update the Data (if new files are added), this takes in data from all the subfolders and makes one pickle file(.pkl) for faster access.
4. Run import data
5. Run Forecasting > input number of months to forecast and number of top products to forecast for
6. The forecasted sum of sales predicted for that period is stored in the ‘forecast_result.xlsx’ file
7. Go through the comments to understand what works how

## Results
Not many parameters were tuned due to time constraints, but sufficiently okay results were obtained because of Prophet's seasonal pattern recogonition.
A few results can be seen in the colab output graphs shown.

Feel free to modify, enhance, or adapt this project according to your requirements. If you have any questions or suggestions, please feel free to reach out.

Happy forecasting!
