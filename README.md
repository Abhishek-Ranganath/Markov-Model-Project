# Airline Delay Forecasting With Markov Chains

A stochastic approach to predicting flight delays by modeling airline delay patterns as Markov processes. This project includes:
- Exploratory data analysis of causes for airline delays
- Markov Chain modeling of delay states
- Transition probability matrix analysis
- Steady-state analysis of long-term delay patterns
- Interactive GUI for making delay predictions
- Airline reliability rating system

## Major Application Features 

1. **Markov Chain Model**:
   - Each delay is categorized into Low (≤15%), Moderate (15 - 25%), and High (>25%) delay states
   - Delay probabilities are weighted and calculated with two methods (entropy and standard deviation)
   - A transition probability matrix for each airline is created

2. **Predictive Analysis**:
   - Markov chain iterations are used to predict future delay distributions
   - The most reliable airline within an airport and timeframe can be identified
   - Delay probabilities can be broken down (low/moderate/high) 

 3. **Steady-State Analysis**:
   - Long-term state probabilities can be calculated for the airlines
   - Delay reasons can be broken down into the dominant cause (carrier/nas/late aircraft)
   - Reliability scores can be produced (0-100 scale) 

 4. **Interactive GUI**:
   - A GUI with easy-to-use interface for airport and period selection
   - Visual output of probability and reasons of delay
   - Optimal airline selection will be recommended

## Key Findings

1. **Delay Cause Correlation**:
   - Strongest correlation (0.89) between carrier delays and late aircraft delays
   - Security delays showed weakest correlation with other delay types

2. **Airline Reliability Scores**:
   - Top performers: 9E (77.27), AS (75.00), EV (74.50)
   - Lowest performers: NK (36.87), AA (25.27)

3. **Dominant Delay Causes**:
   - NAS Delays dominate for 9 airlines (e.g., DL, MQ, OO)
   - Late Aircraft Delays dominate for 6 airlines (e.g., AA, UA, WN)
   - Carrier Delays dominate for 2 airlines (B6, EV)
