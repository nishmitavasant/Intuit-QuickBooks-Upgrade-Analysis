# Intuit QuickBooks Upgrade Analysis

## Project Overview
This project aimed to develop a predictive model to identify small businesses likely to respond to an offer to upgrade to QuickBooks version 3.0. Utilizing data from a wave-1 mailing campaign, our goal was to maximize the effectiveness of Intuit's wave-2 mailing campaign. Advanced predictive modeling techniques, including Logistic Regression and Neural Networks, were employed to analyze business interactions, purchasing history, and prior campaign responses.

## Objective
The primary objective was to refine the selection process for the wave-2 mailing, aiming to increase response rates and maximize the campaign’s overall effectiveness and profitability. This involved evaluating different classifiers, performing extensive hyperparameter tuning, and enhancing model accuracy.

## Key Results
- The optimized logistic regression model achieved an AUC of 0.755, demonstrating strong predictive capability.
- The targeted mailing strategy reached 303,949 businesses, resulting in 25,225 positive responses.
- Generated a projected profit of $1,084,932, with a Return on Marketing Expenditure (ROME) of 253.15%.
- This project won a competition among our MSBA class cohort by achieving the highest profit based on actual campaign responses.

## Repository Contents

- [`intuit_code.ipynb`](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/blob/main/intuit_code.ipynb): Jupyter notebook containing the main analysis and modeling code.
- [`data/`](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/tree/main/data): Data sets used in the analysis.
- [`intuit-quickbooks_case.pdf`](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/blob/main/intuit-quickbooks_case.pdf): PDF document detailing the case study.
- [`writeup.ipynb`](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/blob/main/writeup.ipynb): Additional explanations and write-up of the analysis.
- [`to_target_data.csv`](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/blob/main/to_target_data.csv): Data file containing the list of businesses to target in the wave-2 campaign.

## Technologies Used
- **Predictive Modeling:** Logistic Regression, Neural Networks
- **Performance Metrics:** AUC, Confusion Matrix, Gains and Lift Charts
- **Model Tuning:** Hyperparameter Optimization, Cross-Validation
- **Economic Analysis:** Breakeven Analysis, Campaign Targeting Strategy

## How to Run
1. Clone the repository.
2. Ensure you have Jupyter Notebook installed, or use Google Colab to open the `.ipynb` files.
3. Install necessary Python packages: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `keras`.
4. Run the notebook `intuit_code.ipynb` to view the analysis and modeling steps.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Please ensure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact
For any inquiries, please [open an issue](https://github.com/nishmitavasant/Intuit-QuickBooks-Upgrade-Analysis/issues) on GitHub.
