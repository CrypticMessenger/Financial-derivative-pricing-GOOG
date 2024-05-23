## Option price prediction using Black-Scholes, CRR and Simulation model

## Option Pricing Parameters

| Parameter                         | Value                |
| --------------------------------- | -------------------- |
| sigma (Historical volatility)     | 0.2873627770614688   |
| S0 (Spot Price)                   | 173.69000244140625   |
| r (Risk-Free Rate)                | 0.052379999160766605 |
| T (Time to Maturity)              | 0.09041095890410959  |
| K_call (Strike Price - Call)      | 170                  |
| K_put (Strike Price - Put)        | 180.0                |
| sigma_hat (Forecasted Volatility) | 0.2899623910268287   |

## Option Pricing Results

| Model         | volatility type | call     | put      |
| ------------- | --------------- | -------- | -------- |
| Black-Scholes | Historical      | 8.424078 | 9.194815 |
| CRR           | Historical      | 8.420028 | 9.220725 |
| Simulation    | Historical      | 8.417756 | 9.330980 |
| Black-Scholes | Forecasted      | 8.475106 | 9.246386 |
| CRR           | Forecasted      | 8.472379 | 9.272269 |
| Simulation    | Forecasted      | 8.402203 | 9.112247 |
# option-pricing-analysis-GOOG
