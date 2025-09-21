LPPL Bubble Risk Analyst
An econophysics analysis project to detect and quantify the risk of bubbles in financial assets using the Log-Periodic Power Law (LPPL) Model.
This repository contains a Python notebook that implements the LPPL model to fit to asset price time series and calculate key risk indicators, such as the critical time (t_c) and the Johansen-Ledoit-Sornette (JLS) bubble risk metric.
🌟 Key Features
* LPPL Model Implementation: Functional code for the Log-Periodic Power Law model, an advanced tool for bubble analysis.
* Automated Data Analysis: Retrieves historical price data directly from Yahoo Finance (yfinance).
* Risk Analysis: Calculates the critical time (t_c) —the forecasted collapse date— and the JLS bubble metric, providing a quantification of the risk.
* Comprehensive Visualization: Generates interactive plots with Matplotlib, showing the model fit, data on logarithmic and linear scales, and residuals for an evaluation of the fit quality.
* Customizable: Allows the user to select any financial asset available on Yahoo Finance for analysis.
💻 Installation and Usage
1. Clone the repository:
git clone [https://github.com/pmonsivaisrivera08/LPPL-Bubble-Risk-Analyst.git](https://github.com/pmonsivaisrivera08/LPPL-Bubble-Risk-Analyst.git)
cd LPPL-Bubble-Risk-Analyst

2. Install the necessary dependencies:
pip install pandas numpy scipy matplotlib yfinance

3. Run the notebook:
Open the LPPL_Bubble_Risk_Analyst.ipynb file in Jupyter Notebook or Google Colab and run the cells one by one to see the full analysis.
⚠️ Legal Disclaimer
This project is a research tool and should not be used to make investment decisions. The LPPL model is a risk analysis tool based on the identification of historical patterns. It is not an infallible market prediction and the results should be interpreted with caution. The author and contributors are not responsible for any financial loss or damage resulting from the use of this code.
🤝 Contributions
Contributions are welcome. Feel free to open an issue or submit a pull request with improvements, bug fixes, or new features.
📄 License
This project is licensed under the MIT License.