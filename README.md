# Implement Drop connect and compare with Drop out on mnist dataset
drop connect paper : http://proceedings.mlr.press/v28/wan13.pdf
# Compare result
both train 10 epoch
|method | train loss | train accuracy | val loss | val accuracy | test loss | test accuracy | 
|---|---|---|---|---|---|---|---|
|drop out | 0.0164 | 0.9949 | 0.0481| 0.9906  | 0.9904 |
|drop connect | 0.0267 | 0.9912 | 0.0754 | 0.9806 | 0.9869 |
