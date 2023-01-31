# homework
# Spam_detection
## 环境
a) Linux/Windows python 3.6  
b) 所需的 python 模块 matplotlib==3.3.3 nltk==3.5 joblib==0.17.0
scikit_learn==0.23.2  
c) nltk_data(http://www.nltk.org/data.html) 

数据来源：https://www2.aueb.gr/users/ion/data/enron-spam/

## 使用介绍


```
python Collecting_samples.py(将 Spam 文件夹和 Legitimate 文件
夹中的垃圾邮件和合法邮件收集并重命名放入 Samples 文件夹，
垃圾邮件重命名方式 S-样本编号.txt；合法邮件重命名方式 L-样
本编号.txt)  

python Data_cleaning.py(进行数据清洗) ---不用运行

python Creating_word_dictionary.py(创建词典) --可以运行，也可以不运行 

python Mail_classification.py(训练分类器输出准确率等信息，保存训
练测试所用的文件)  ----可以运行，也可以不运行 
  
python Accuracy_analysis.py(划分数据集并输出在划分后的数据集上
分类器的准确率，精准度，召回率，最后保存训练后的模型) 
--想得到这些指标就运行
  
python Spam_Detector.py(对 Email_list 文件夹中的邮件进行判断，输
出判断结果)  --想测试新的文件，就增加或者减少 Email_list 文件夹中的文件后运行，也可以直接运行

```

![image-20230128222016756](README.assets/image-20230128222016756.png)

<img src="README.assets/image-20230128222935196.png" alt="image-20230128222935196" style="zoom:50%;" />

<img src="README.assets/image-20230128223013423.png" alt="image-20230128223013423" style="zoom:50%;" />
