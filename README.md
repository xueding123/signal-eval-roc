# 机器学习增强的CRISPR/Cas14a双信号生物传感系统用于骨质疏松诊断

本仓库包含论文《Machine learning-enhanced CRISPR/Cas14a dual-signal biosensing system for osteoporosis diagnosis and monitoring》的机器学习部分分析代码。

## 文件说明

### `CRISPR_Cas14a_SVM_ROC_Analysis.ipynb`
- SVM算法的ROC曲线分析
- 专注于SOST1+SOST2特征的分类

### `Osteoporosis_ML_Algorithm_Comparison.ipynb`

- 六种机器学习算法比较
- 包括SVM、随机森林、逻辑回归、KNN、决策树、LDA
- 支持SOST和Signal两种特征分析

### `Dual_Signal_Classification_Analysis.ipynb`
- 双信号分类分析
- 基于Signal1(COL)和Signal2(FL)特征
- 生成混淆矩阵和性能评估

## 主要特点

- 双信号检测（荧光信号FL + 比色信号COL）
- 三分类诊断（健康、骨量减少、骨质疏松）
- 多种机器学习算法比较

## 运行环境

需要安装：pandas, numpy, matplotlib, seaborn, scikit-learn, openpyxl

## 使用方法

1. 准备数据文件（Excel格式）
2. 按顺序运行notebook文件
3. 结果图表自动保存到指定目录

## 主要结果

SVM算法在SOST特征上达到99.6%的AUC值，显示出优秀的分类性能。