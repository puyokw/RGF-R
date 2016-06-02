# RGF-R
a few R functions for using Reguralized Greedy Forest easily

# example of usage
```R
RGFCV(train,target,nround=1500,lambda=0.1,nfold=5)
pred <- RGF(train,test,target,nround=1300,lambda=0.1)
submission <- data.frame(id=id, probability=pred$prediction)
```
