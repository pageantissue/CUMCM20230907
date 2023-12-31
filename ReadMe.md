# CUMCM20230907
2023/09/07高教社杯_C题省一等奖
## 小组成员 SCUT 未来技术学院数据科学与大数据技术一班
* 杨裕钦
* 邓靖丰
* 石寒雪


# 国赛数模竞赛支撑材料文件说明

## 文件目录结构

在提交文件中，包含以下文件和文件夹：

- `README.md`: 提交文件结构说明文档。
- `workplace/`: 存放代码文件。
- `data/`: 存放清洗数据和生成的图例。
- `report.pdf`: 论文的PDF版本。
- `result/`: 存放三个自文件夹`Q1/`, `Q2/`,`Q3`，分别存放第一、二、三问的结果文件。



## 代码文件

代码文件均放置在 `workplace/` 文件夹中。

- `workplace/Q1_数据处理与可视化.ipynb`: Q1_数据处理与可视化.ipynb：Q1的数据预处理以及销售量可视化
- `workplace/Q1.ipynb`: Q1的相关性分析，热力图绘制，层次聚类分组，等次树状图。
- `workplace/Q2.ipynb`: Q2价格-销售重量关系的回归分析
- `workplace/Q2_ARIMA.ipynb`: Q2价格-批发价的补全和预测
- `workplace/Q2&3_模型求解.ipynb`: Q2与Q3问题的多目标优化问题



## 数据文件

问题求解的中间数据文件放置在 `data/` 文件夹中，包含所有代码文件用到的中间数据和代码生成的图例。

`data/批发销售数据_品类`： 以品类为单位 统计的批发销售结果
`data/销售单价`：  以品类，单品为单位 统计的销售单价结果
`data/销售量数据`： 以品类，单品为单位 统计的销售量数据结果
`data/销售折线图`： 以品类，单品为单位 统计的销售折线图



## 结果文件

问题求解的结果数据文件放置在 `result/` 文件夹中，包含所有用到的中间数据。

`result/Q1/interpolated`： 未归一化可视化以及结果，包含相关性热力图，相关性层次聚类分组映射，以及层次树状图
`result/Q1/standardized`： 归一化可视化以及结果，包含相关性热力图，相关性层次聚类分组映射，以及层次树状图
