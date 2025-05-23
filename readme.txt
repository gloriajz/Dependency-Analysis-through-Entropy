Dataset Overview
This project uses several datasets sourced from Bloomberg’s Climate Risk and Carbon Emissions Data category to explore the dynamics of the European Union Emission Allowances (EUA) market and its interactions with various financial and climate-related indicators.
Datasets Included:
1. European Union Emission Allowances (EUA) Futures - MO1.csv
   * Description: This dataset contains daily closing prices and trading volumes for the ICE ECX EUA Futures Contract (ticker: MO1 Comdty), the most liquid instrument in the EU carbon market. The data spans from January 2010 to December 2022, capturing critical periods of policy interventions and market shifts.
   * Fields:
      * Date: The date of the trading day
      * Close: Daily closing price of the EUA Futures Contract
      * Volume: Trading volume for that day
      * Open, High, Low: Price data for each trading day
   * Usage: This data is used to examine price movements and trading volumes in the EUA market, focusing on nonlinear dependencies.
2. Bloomberg Carbon Emissions Index - CARN.csv
   * Description: The CARN dataset tracks the performance of a basket of carbon-related assets, serving as a benchmark for the emissions trading market. Data is provided weekly from January 2010 to December 2022.
   * Fields:
      * Date: Week-ending date
      * Index Value: Value of the Carbon Emissions Index
   * Usage: This index is used to provide an aggregate view of the carbon market’s performance and assess the market’s sensitivity to regulatory changes.
3. Bloomberg Climate Transition Risk Index - CLTRISK.csv
   * Description: The Climate Transition Risk Index (ticker: CLTRISK) tracks industries’ exposure to risks arising from policy transitions aimed at reducing carbon emissions. Data is available monthly from January 2010 to December 2022.
   * Fields:
      * Date: The month-end date for each observation
      * Index Value: Climate transition risk score for the period
   * Usage: The index is used to explore how policy-driven risks influence the EUA market and examine nonlinear dependencies in response to policy changes.
4. S&P Global Clean Energy Index - SPGTCLEN.csv
   * Description: This index tracks the performance of companies involved in the clean energy sector, such as renewable energy producers and technology firms. Data is provided daily from January 2010 to December 2022.
   * Fields:
      * Date: The date of the trading day
      * Index Value: Daily value of the Clean Energy Index
   * Usage: This data is used to analyze the interaction between carbon pricing and the broader clean energy market, examining potential hedging or diversification strategies.
5. VIX Index - VIX.csv
   * Description: The VIX Index (ticker: VIX Index) represents the market's expectation of volatility over the coming 30 days. It is widely used as a proxy for overall market uncertainty. The data spans from January 2010 to December 2022.
   * Fields:
      * Date: The date of the observation
      * VIX Value: Volatility index value for that day
   * Usage: The VIX is used to assess how market volatility influences trading in the EUA and other carbon-related markets.