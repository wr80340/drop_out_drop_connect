# Implement Drop connect 
drop connect paper : http://proceedings.mlr.press/v28/wan13.pdf  
# Introdction
In this project, we implement drop connect, which is introduced in the paper above,
and compare it with drop out, which is a popular regularizer to prevent overfitting.
In conclusion, the results of drop out performs better, maybe drop out is enough for regularization.

# Compare result
both train 10 epoch  

method | train loss | train accuracy | val loss | val accuracy | test accuracy 
---|---|---|---|---|---
drop out | **0.0164** | **0.9949** | **0.0481**| **0.9906** | **0.9904** 
drop connect | 0.0267 | 0.9912 | 0.0754 | 0.9806 | 0.9869 
