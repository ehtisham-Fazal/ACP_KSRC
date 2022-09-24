# ACP_SRC
implementation of Sparse Representation classifier on Anticancer piptides

| DATA_SET          | ACP | NON_ACP |
|-------------------|-----|---------|
| ACP_740           | 376 | 364     |
| COMBINED_DATA_SET | 505 | 475     |
| ACP_344           | 138 | 206     |

Performance Results:
| model                      | SEN   | SPEC  | F1_SCORE | B_ACC | Y_I   | MCC   |
|----------------------------|-------|-------|----------|-------|-------|-------|
| ACP_SRC_740                | 83.51 | 83.48 | 83.35    | 83.50 | 67.00 | 67.11 |
| ACP_SRC_COMBINED_DATA_SET  | 78.10 | 81.18 | 78.91    | 79.64 | 59.29 | 59.41 |
| ACP_LSTM_COMBINED_DATA_SET | 79.60 | 77.87 | 77.87    | 78.84 | 57.68 | 57.82 |
| ACP_SRC_344                | 96.14 | 87.63 | 94.11    | 91.89 | 83.78 | 85.22 |
