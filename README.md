# 加拿大银行抵押品报告

[English version](README_EN.md)

本报告的目的是向加拿大银行提供相关抵押品的数据。

这些数据对于评估交易对手方与活动之间的联系以及确定不同资产类别之间交易的规模是十分重要的。

此报告使用SQL对原始Excel数据进行提取，整理，处理，分析等。

由此达到报告目的并为加拿大银行提供数据分析后的有效商业建议。

## 背景资料

此业务只在工作日内进行。工作日定义为除联邦和省级法定假日外的所有工作日。

所附模板标识了只需要在每月底更新数据。每个工作日都需要在表格内填写相应数据。

![](Objective.png)

### 资产类型定义

一级资产:政府债券

二级资产:非金融公司债券/股权，信用评级在A - AAA之间。

第三级资产:金融公司债券/股权，或非金融公司债券/股权，信用评级低于A。

### 原始数据
[Collateral transactions as of Jul 2016](原始数据/collateraltransaction.csv)

[Security instrument details](原始数据/security.csv)

[Counterparty details](原始数据/customer.csv)

