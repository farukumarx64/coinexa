# Coinexa

Coinexa is a cryptocurrency portfolio tracker and investment simulator powered by the DeCommas Mission Control API. It allows users to seamlessly track their cryptocurrency holdings, simulate investments, and visualize their portfolio data. This project was developed for the buidlHACKS hackathon.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Portfolio Tracking:** View real-time data of your cryptocurrency holdings, including assets, quantities, and current market values.
- **Investment Simulation:** Simulate cryptocurrency investments to test different trading strategies without risking real money.
- **Visualization:** Interactive charts and graphs to visualize the distribution of assets and track gains/losses over time.
- **User Authentication:** Secure user accounts with authentication mechanisms.
- **User Profile:** View and edit user profile information and linked wallet addresses.

## Installation

To run Coinexa locally, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/farukumarx64/coinexa.git
   ```

2. **Navigate to the project directory:**
   ```sh
   cd coinexa
   ```

3. **Install dependencies:**
   ```sh
   npm install
   ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

5. **Access Coinexa in your browser:**
   ```sh
   http://localhost:3000
   ```

## Usage

1. **Add Your Wallet Address:**
   - Connect your blockchain wallet addresses to start tracking your portfolio.

3. **Track Your Portfolio:**
   - View your real-time cryptocurrency holdings and transaction history.

4. **Simulate Investments:**
   - Use the investment simulator to test different trading strategies.

5. **Visualize Data:**
   - Explore interactive charts and graphs to understand your portfolio's performance.

## API Integration

Coinexa utilizes the DeCommas Mission Control API to fetch real-time cryptocurrency data. Ensure you have API keys from DeCommas and set up the necessary environment variables.

- **Environment Variables:**
  - `REACT_APP_DECOMMAS_API_KEY`: Your DeCommas Mission Control API key.

## Contributing

We welcome contributions from the community! If you have any feature suggestions, bug reports, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---