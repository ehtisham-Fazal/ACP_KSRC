# ACP_SRC
implementation of Sparse Representation classifier on Anticancer piptides                                                 
Data_set used for different models scraped from below given links

  1_for acp_344:
  
  a. https://raw.githubusercontent.com/Shujaat123/ACP_LSE/main/dataset_acp_JTB_2014/1-s2.0-S0022519313004190-mmc1.txt.
  
  b. https://raw.githubusercontent.com/Shujaat123/ACP_LSE/main/dataset_acp_JTB_2014/1-s2.0-S0022519313004190-mmc2.txt
  
  2_for acp_740 and acp_240 :
  
  a. https://raw.githubusercontent.com/haichengyi/ACP-DL/master/acp740.txt
  
  b. https://raw.githubusercontent.com/haichengyi/ACP-DL/master/acp240.txt
  
  
  NOTE:Due to any reason if you cannot download data set from above link then data set also available in our Data_set.zip folder.
  
  
 No of ACP and NON-ACP in data set are given below: 
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


we have implemented our SRC model on acp_740 data_set ,Combine both acp_740 and acp_240 data set and then implement our SRC model and LSTM model from ACP_DA paper[1].
we have also implemented our SRC model on ACP_344 data set and compare our result with paper[2]. Our model perfomance on both data_Set is better than papers model.

Refrences:

1.https://www.frontiersin.org/articles/10.3389/fgene.2021.698477/full

2.https://www.frontiersin.org/articles/10.3389/fbioe.2020.00892/full
