# Fraud_Detetction

Fraud detection is often seen as a black-box machine learning task, but SQL investigations can reveal powerful insights before we write a single model. I wanted to simulate how an analyst might explore financial fraud using structured queries.

PaySim on Kaggle is a mobile money simulator based on real transaction patterns, featuring over 6 million entries across:
- Transaction types: TRANSFER, CASH_OUT, PAYMENT, DEBIT, CASH_IN
- Account information: sender/receiver IDs and balances
- Fraud flags: isFraud and isFlaggedFraud

Link to data: https://www.kaggle.com/datasets/ealaxi/paysim1
PaySim paper of the simulator:
E. A. Lopez-Rojas , A. Elmir, and S. Axelsson. "PaySim: A financial mobile money simulator for fraud detection". In: The 28th European Modeling and Simulation Symposium-EMSS, Larnaca, Cyprus. 2016

Questions/Themes the SQL project 'fraud.ipynb' looks at: 
1. How big is fraud?
2. What type of transactions constituted fraud?
3. Did current system in place identify fraud transactions as fraudulent?
4. Since steps are hours - are there certain times when there is more fraudulent activity than others?
5. is there a spike in activity for certain accounts?
6. Are there Outliers? - high stakes.
