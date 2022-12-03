# High Gas Contract Creation Monitoring

## Description

This bot was designed for tracking the creation of contracts, with a gas price threshold for information only. There are bots that do some of this individually but this bot seeks to be a medium between other approaches. Mainly between an alert for Information vs Suspicion. 

## Supported Chains

- Ethereum
- Optimism
- BSC
- Polygon
- Fantom
- Arbitrum
- Avalanche

## Alerts

The alert for this detection bot is information. The threshold of gas used is not an alarming amount and only slightly above something that would warrant medium severity. This bot does not have the intention of alerting to suspicion but rather creating an inormation pool for contracts that are created with higher than normal gas.  

- FORTA-8
  - Fired when a transaction is of type 'create' and has a used gas beyond the threshold
  - Severity is always set to "info".
  - Type is always set to "info".

