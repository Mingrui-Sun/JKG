# 司法知识图谱研究Judicial Knowledge Graph

1 MultinomialNB_code.ipynb —— 基于朴素贝叶斯模型的司法知识图谱构建算法

            Accuracy: 0.8942961800104657
                      precision    recall  f1-score   support
        
                 NDR       1.00      1.00      1.00       831
                  NT       1.00      0.99      1.00       541
                  NW       0.98      0.92      0.95       401
                  Nh       0.80      1.00      0.89      1610
                  Ns       1.00      0.16      0.28       439
        
            accuracy                           0.89      3822    
           macro avg       0.96      0.82      0.82      3822   
        weighted avg       0.91      0.89      0.87      3822

2 results文件，将提取的实体和关系数据以JSON格式进行存储

3 train.json文件为项目所使用的数据集，采用交叉验证进行测试



