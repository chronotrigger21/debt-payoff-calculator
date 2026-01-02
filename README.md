# Debt Payoff Calculator

A simple, single-page web application that helps you create a plan to pay off your debts. Enter your debt accounts, choose a payoff strategy, and visualize your path to becoming debt-free.

## Features

- **Multiple Debt Types**: Track credit cards, personal loans, student loans, and other debts
- **Payoff Strategies**:
  - **Avalanche Method**: Pay off highest interest rate debts first (minimizes total interest paid)
  - **Snowball Method**: Pay off smallest balances first (quick wins for motivation)
- **Promotional Rate Support**: Handle credit card balance transfers and intro APR offers with scheduled rate changes
- **Extra Payments**: See how additional monthly payments accelerate your debt payoff
- **Interactive Visualizations**: Chart showing debt balances over time
- **Detailed Schedule**: Month-by-month breakdown of payments, principal, interest, and balances
- **Data Persistence**: Your debts are automatically saved to browser localStorage
- **Export/Import**: Download your data as JSON or restore from a backup file
- **Light/Dark Mode**: Toggle between light and dark themes

## How to Use

1. **Add Your Debts**: Enter the account name, debt type, current balance, APR, and monthly payment for each debt
2. **Add Promotional Rates** (optional): If a debt has a temporary intro rate, check the promo box and enter the promo APR and end date
3. **Choose a Strategy**: Select Avalanche (highest interest first) or Snowball (smallest balance first)
4. **Set Extra Payment** (optional): Enter any additional amount you can pay beyond minimums
5. **Calculate**: Click "Calculate Payoff Plan" to see your results
6. **Review**: Check your debt-free date, total interest, payoff order, and detailed schedule

## Tech Stack

- **HTML5** / **CSS3** / **Vanilla JavaScript**
- **Chart.js** for visualizations (loaded via CDN)
- **No build step required** - just open `index.html` in a browser

## Running Locally

Simply open `index.html` in any modern web browser. No server or installation required.

```bash
# Clone the repository
git clone https://github.com/chronotrigger21/debt-payoff-calculator.git

# Open in browser
open index.html
# or on Linux:
xdg-open index.html
```

## Data Privacy

All data is stored locally in your browser's localStorage. Nothing is sent to any server. Use the Export feature to back up your data.

## License

MIT License - feel free to use and modify as needed.
