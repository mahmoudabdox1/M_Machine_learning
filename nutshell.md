Data: 
    - source
    - features names
    - no samples "entries,row"
    - no features "columns"
    - range of each features "histogram"
    - types
    - relation between label and inputs if supervised
    - relation between inputs and each other if unsupervised
    - null treatment
    - label encoding vs one hot key encoding
    - splitting
    - Scaling


Model:
    Supervised vs Unsupervised:
    Supervised: Regression vs classification
        Regression: 
            types:LR, SVM, DT,RF,GBDT,NN
            metrics:MAE,mse,r2score,rmse,mape
        classification:
            types:Logistic regression, svm, DT, RF, GBDT, NN
            metric: confusion matrix, recall, precision, f1score, auc
    Unsupervised:
        clustering: 
            type:kmean
            metric: look to the script
        other:
            PCA