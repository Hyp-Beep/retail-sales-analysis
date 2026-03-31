# 零售订单数据分析项目
基于70690条零售设备订单数据，完成从数据清洗、多表关联、SQL存储到可视化分析的全流程项目。

## 技术栈
- Python（Pandas数据处理、Matplotlib可视化）
- SQL Server（数据存储与多维度聚合查询）
- Git & GitHub

## 文件说明
- `data1.csv`：原始订单数据
- `data2.csv`：商品分类数据
- `main.py`：项目主程序
- `load.py`：数据加载模块
- `plot.py`：可视化绘图模块
- `db_tools.py`：SQL Server数据入库脚本
- `retail_analysis.sql`：核心分析SQL脚本

## 核心结论
- 总订单量70690条，总销售额285898.50元
- E点位贡献约33%销售额，为核心盈利点位
- 饮料与非饮料品类销量均衡，商品结构健康
