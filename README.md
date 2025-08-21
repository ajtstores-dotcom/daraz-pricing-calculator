# Daraz.pk Pricing Calculator

## Overview
The Daraz.pk Pricing Calculator is a free, web-based tool designed for sellers on Daraz.pk (Pakistan) to calculate recommended selling prices or test specific selling prices for their products under the Fulfilled by Merchant (FBM) model. It helps sellers optimize pricing by factoring in making/buying costs, desired profit margins, and Daraz fees (commission, payment processing, handling, and VAT). The tool supports calculations for one product or up to five products simultaneously, with product names (max 50 characters) required for multiple products.

## Features
- **Calculation Modes**:
  - **Recommended Price**: Calculates the optimal selling price based on cost, desired profit margin (percentage or rupees), and Daraz fees.
  - **Test Selling Price**: Evaluates profit or loss for a user-specified selling price.
- **Fee Breakdown**: Displays detailed Daraz fees (commission, payment processing, handling, and VAT) and actual cost.
- **Responsive Design**: Mobile-friendly interface with clean, user-friendly styling.
- **Profit/Loss Indicators**: Results are color-coded (green for profit, red for loss, neutral for breakeven).
- **Handling Fee Reference**: Includes a table of Daraz's tiered handling fees based on selling price.

## How to Use
1. **Access the Tool**: Open `index.html` in a browser or visit the deployed site (e.g., via GitHub Pages).
2. **Choose Calculation Type**:
   - Select "Calculate Recommended Price" or "Test Selling Price."
   - For Recommended Price, specify profit margin type (percentage or rupees).
3. **Enter Inputs**:
   - **Making/Buying Cost**: Cost to produce or acquire the product (Rs.).
   - **Desired Profit Margin**: Percentage or fixed rupees (for Recommended Price).
   - **Category Commission**: Daraz's commission percentage for the product category.
   - **Payment Processing Fee**: Default is 2.5%, editable.
   - **VAT**: Optional, based on province (default 0 if blank).
   - **Test Selling Price**: Required for Test Selling Price mode.
4. **Calculate**: Click the "Calculate" button to view results, including recommended price, fee breakdown, actual cost, and profit/loss.



## File Structure
- `index.html`: Main file containing the calculator, CSS, and JavaScript.
- `README.md`: This file, providing project overview and instructions.

## Future Enhancements
- Add export functionality to download results as CSV or PDF.
- Include advanced fee calculations (e.g., promotions, shipping).
- Enhance UI with additional styling or interactive charts.

## License
This project is open-source under the apache2.0 License. Feel free to use, modify, and distribute, but include attribution to the original author.

## Contact
For issues or suggestions, open a GitHub issue or contact ajt.stores@gmail.com.
