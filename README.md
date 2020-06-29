# Credit_Card_Default_Risk
EDA + Predictive Modeling

# 「 数据 」


TW某银行客户信用卡数据：

（人口统计特征、信用数据、历史还款、账单等）

2005年4月-2005年9月

30k 条

25个Variables

本数据集无空值



🔑目标：针对历史欠款数据，为信贷风控人员提供风险评估依据，对客户是/否违约做出预测。




# 「 变量 」

LIMIT_BAL
信用额度 包括个人和家庭/追加
SEX
性别
1 = 男 、2 = 女
EDUCATION
教育程度
1 = 研究生、2 = 大学、3 = 高中、4 = 其他
MARRIAGE
婚姻状况
1 = 已婚、2 = 未婚、3 = 其他
AGE
年龄
PAY_0
PAY_2
...
PAY_6
还款状态
-2: 未消费、-1：如期还款、0：循环信贷、1：付款延迟1个月、 2：付款延迟2个月...以此类推到 9: 付款延迟9个月及以上
PAY_0: Sep， PAY_2: Aug ....PAY_6：April
BILL_AMT1
...
BILL_AMT6
账单金额
6个月内每月情况:
BILL_AMT1 : Sep， BILL_AMT2: Aug ....BILL_AMT6：April
PAY_AMT1
...
PAY_AMT6
还款金额
6个月内每月情况
PAY_AMT1 : Sep， PAY_AMT2: Aug ....PAY_AMT6：April
default
是否违约
1 = 是、0 = 否



# 「 算法 」

本期要解决的问题是信用卡用户是/否违约，属于有Label的监督式学习(Supervised Learning)中的分类(Classification)问题。用到的算法包括：

逻辑回归 Logistic Regression

决策树 Decision Tree

随机森林 Random Forest

K邻近算法 K-Nearest Neighbours



# 分类问题 Classification

# Machine Learning

1. 数据清理 Data Cleaning & EDA

2. 独热编码 One-Hot Encoding

3. 标准化 Normalization

4. 过采样 Oversampling

5. 预测建模 Predictive Modeling

6. 模型评估 Model Comparison
