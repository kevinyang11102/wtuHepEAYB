# B站数据可视化分析与个性化推荐系统 python27

本项目是基于 django 和 spark 的 B站数据可视化分析和个性化推荐系统。项目综合运用了视频数据分析、可视化大屏、视频爬虫、大数据处理、知识图谱以及机器学习技术。

## 技术栈

- **后端**: Python 3, Django, Spark, Hive SQL, Sqoop
- **前端**: Vue, Element
- **数据库**: MySQL 5.7+, HDFS

## 功能模块

### 数据获取

- 使用 Python 编写的爬虫，针对 B站 进行数据抓取。

### 数据清洗

- 利用 Pandas 对抓取的原始数据进行清洗。

### 数据存储

- 清洗后的数据存储到 HDFS（Hadoop Distributed File System）。

### 数据分析

- 采用 Hive SQL 对存储在 HDFS 上的数据进行深入分析。
- 分析后的数据通过 Sqoop 导出到 MySQL 数据库。

### 数据可视化

- 使用 Echarts 对分析后的数据进行可视化展示。

### 推荐算法

- 采用 Spark 实现 ALS（交替最小二乘）推荐算法，依据用户行为数据进行推荐建模。

### 机器学习播放量预测

- 基于播放量数据，运用 XGBOOST 模型和随机森林模型进行预测分析。

## 系统角色

- 数据爬取与清洗：负责原始数据的获取与预处理。
- 数据存储与处理：负责数据的分布式存储和大规模数据处理。
- 数据分析与展示：负责数据的深入分析和前端可视化。
- 个性化推荐：负责构建推荐模型，提供个性化推荐。

## 运行环境

- Python 3 环境配置
- Spark 环境搭建
- Vue.js 前端开发环境
- MySQL 数据库服务器

## 部署步骤

1. 环境搭建（Python 3, Spark, MySQL, Hadoop, Hive）
2. 后端服务部署（Django）
3. 前端界面部署（Vue.js）
4. 数据爬取模块部署
5. 数据处理与存储模块部署
6. 数据分析与可视化模块部署
7. 推荐算法与机器学习模块部署

## 目录结构

```markdown
/
├── backend            # 后端代码目录
│   ├── django_app     # Django 应用目录
│   ├── spark_jobs     # Spark 任务代码目录
├── frontend           # 前端代码目录
│   ├── src            # Vue.js 源码目录
├── data_processing    # 数据处理脚本目录
└── data_visualization # 数据可视化脚本目录
```

## 核心亮点

- 基于大数据技术（Spark, HDFS, Hive SQL）进行高效数据处理。
- 利用机器学习算法（XGBOOST, 随机森林）进行播放量预测。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/350614/24/6883/34989/68d2c5beF2cde6af3/85f122be58177e18.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/333280/7/16717/118640/68d2c5beFdf4ea559/6939f5ca52031c81.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/351245/4/6746/53161/68d2c5bfFc2f54931/fdbe2eef9b76144b.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/351225/32/6783/69594/68d2c5bfFd6c5df59/224c44a4949e62f8.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/333659/39/16498/91993/68d2c5c0F089f1605/1a8049c6e87f68c1.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/331801/5/16602/31384/68d2c5c0Faa7d501e/fb8167f45ca97867.jpg)
