# Crypto_Currency_Market_Financial_Risk_Management
## Overview
This project explores financial risk management in the cryptocurrency market using **machine learning techniques**, specifically **Hierarchical Risk Parity (HRP)** and **Reinforcement Learning (RL)**. The study aims to improve risk assessment and portfolio management by leveraging AI-driven strategies.

## Features
- **Risk Evaluation:** Identification and assessment of **inherent risks** in cryptocurrency investments.
- **Hierarchical Risk Parity (HRP):** Portfolio optimization using hierarchical clustering techniques.
- **Reinforcement Learning (RL):** Adaptive risk management for digital assets.
- **Comparative Analysis:** Evaluation against traditional risk-based portfolio strategies.
- **Data-Driven Insights:** Analyzes historical cryptocurrency price trends from **2017 to 2020**.

## Technologies Used
- **Python**
- **Machine Learning (scikit-learn, TensorFlow, PyTorch)**
- **Data Processing (Pandas, NumPy)**
- **Financial Modeling & Analysis**

## How to Use
1. Clone this repository:
   ```sh
   git clone https://github.com/GirendraVarma/MACHINE-LEARNING-BASED-ANALYSIS-OF-CRYPTOCURRENCY-FINANCE-MARKET-AND-RISK-MANAGEMNT.git
   ```
2. Install the app dependencies:
   ```sh
   pip install Django pandas numpy matplotlib seaborn scikit-learn openpyxl
   ```
3. Open a PowerShell terminal, generate a secret key for this terminal session, and enter the app directory:
   ```sh
   $env:DJANGO_SECRET_KEY = (& python -c "import secrets; print(secrets.token_urlsafe(50))")
   cd crypto_currency_market_financial_risk_management
   ```
4. Set up the database and start the Django app:
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```
5. Open http://127.0.0.1:8000 in your browser.

## Dataset
- The project utilizes **cryptocurrency price data** from **CoinMarketCap** (2017-2020).
- Data preprocessing is performed to handle missing values and normalize inputs.

## Results
- Demonstrates **risk reduction** in portfolio management.
- HRP-based asset allocation provides **better risk-return trade-offs**.
- Reinforcement Learning enhances **decision-making strategies** in crypto trading.

## Contributors
- **Abhilash Myana**
  [GitHub Repository](https://github.com/AbhilashMyana-sys)
- **Devendra Varma**
  [GitHub Repository](https://github.com/devendra-varma07)
- **Snehith Kamani**
  [GitHub Repository](https://github.com/AbhilashMyana-sys)
- Based on research by Zeinab Shahbazi & Yung-Cheol Byun

## License
This project is licensed under the **MIT License**.
