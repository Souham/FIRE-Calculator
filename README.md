

# FIRE Calculator 🔥

A simple Python-based calculator to help users estimate their Financial Independence, Retire Early (FIRE) target and calculate how long it will take to reach it based on their savings and investment returns.

## Overview

This FIRE Calculator app lets users input their annual expenses, current savings, expected annual savings, and anticipated investment return to calculate:
- **FIRE Target**: The amount needed to retire based on a specified withdrawal rate.
- **Years to FIRE**: The time required to reach financial independence given the inputs.

The app is built with Python and Streamlit, making it easy to use and visualize results.

## Features

- Input fields for essential parameters:
  - Annual expenses
  - Withdrawal rate (adjustable)
  - Current savings
  - Annual savings
  - Investment return rate
- Calculation of FIRE target based on the 4% rule (or user-defined withdrawal rate).
- Estimation of years required to reach the FIRE target.

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/FIRE-Calculator.git
    cd FIRE-Calculator
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

4. Open the app in your browser (usually at `http://localhost:8501`) and input your financial information.

## Parameters

- **Annual Expenses**: Your expected annual expenses in retirement.
- **Withdrawal Rate**: The rate at which you plan to withdraw from your savings (default is 4%).
- **Current Savings**: The amount you have saved so far.
- **Annual Savings**: The amount you save each year.
- **Investment Return**: Expected annual return rate on your investments.

## Example Calculation

Suppose you have the following inputs:
- Annual Expenses: $40,000
- Withdrawal Rate: 4%
- Current Savings: $100,000
- Annual Savings: $15,000
- Investment Return: 7%

The app will calculate:
- **FIRE Target**: $1,000,000
- **Years to FIRE**: Approx. 27 years

## Deployment

The app can be deployed with Streamlit Cloud:
1. Push your repository to GitHub.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and link your repository.
3. Set the main script path to `app.py` and deploy!

## Contributions

Feel free to open issues or pull requests if you want to add features or fix bugs.

## License

This project is licensed under the MIT License.

## Acknowledgments

Inspired by the FIRE movement and built to help simplify financial planning.

Happy calculating! 🚀
