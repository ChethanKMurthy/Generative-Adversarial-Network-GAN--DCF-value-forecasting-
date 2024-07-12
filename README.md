# AI-Driven Financial Forecasting & Valuation of Major Indian Banks

## Overview

This project utilizes artificial intelligence techniques, specifically Generative Adversarial Networks (GANs) and Discounted Cash Flow (DCF) modeling, to analyze historical financial data of major Indian banks. The goal is to forecast future financial scenarios and evaluate investment potential to identify optimal investment choices.

## Working of the Project

### 1. Data Collection

- **Objective:** Gather historical financial data for major Indian banks.
  
- **Implementation:** Utilize the `yfinance` library in Python to fetch daily closing prices for HDFC, SBI, ICICI Bank, Axis Bank, Kotak Mahindra Bank, IndusInd Bank, Yes Bank, and Punjab National Bank (PNB).
  
- **Data Preprocessing:** Clean and preprocess the data to handle missing values, calculate daily returns, and normalize the data if necessary.

### 2. Generative AI Model Development

- **Objective:** Generate realistic future financial scenarios using GANs.

- **Implementation:**
  - **Generator Network:** Develop a generator model to create synthetic financial data based on historical trends.
  - **Discriminator Network:** Build a discriminator model to distinguish between real and generated financial data.
  - **Training:** Train the GAN to improve the generator's ability to produce realistic financial scenarios.

### 3. Discounted Cash Flow (DCF) Modeling

- **Objective:** Evaluate investment potential using DCF modeling techniques.

- **Implementation:**
  - **Free Cash Flow (FCF) Projection:** Estimate future Free Cash Flows (FCF) based on generated financial scenarios.
  - **Discount Rate Selection:** Determine appropriate discount rates (e.g., cost of equity) to calculate the present value of future cash flows.
  - **Net Present Value (NPV) Calculation:** Compute NPV by discounting projected FCFs and assessing the investment's present value.
  - **Sensitivity Analysis:** Perform sensitivity analysis by varying inputs (e.g., discount rates) to understand their impact on investment decisions.

### 4. Investment Recommendation

- **Objective:** Identify the optimal investment choice based on NPV analysis.

- **Implementation:** Compare NPVs calculated for each bank to determine the bank with the highest NPV, indicating the optimal investment opportunity.

### 5. Output and Visualization

- **Objective:** Present analysis results in an understandable format.

- **Implementation:**
  - **Visualization:** Use matplotlib or similar libraries to plot graphs comparing NPVs of different banks.
  - **Reporting:** Generate summary reports or output files that highlight key findings and the recommended investment choice.




