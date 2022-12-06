
* Primer entrega

| Score | Clasificador |
|--------|-------|
|89%     | XGB   |
|80%     | MLP   |
|79.86%  | Random Forest |
|76.86%  | Random Tree |


```
(0.8936740608754178, XGBClassifier(colsample_bytree=0.5, learning_rate=0.2, subsample=0.8))
(0.8029912748449695, MLPClassifier(activation='tanh', batch_size=20, hidden_layer_sizes=9,
              learning_rate='adaptive', max_iter=15000, random_state=17,
              solver='sgd'))
(0.7686241976943247, DecisionTreeClassifier(max_leaf_nodes=8))
(0.798665655555197, RandomForestClassifier(max_depth=14))
```
