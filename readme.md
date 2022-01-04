# 环境空气质量评价挑战赛文件说明

* 比赛链接http://challenge.xfyun.cn/topic/info?type=air-quality

* 初赛成绩0.00413第8，复赛1.08435第6

* 运行方式：先运行Sub00_IPRC_Trn159_Val177.ipynb，再运行Sub01_FS_AQI_Val2.848.ipynb，运行路径下的sub文件夹中生成sub.csv文件即为结果文件。

* 运行环境

  ```
  lightgbm=3.2.1
  numpy=1.18.5
  pandas= 1.2.4
  scikit-learn=0.24.2
  tqdm=4.60.0
  ```

  

* Sub00_IPRC_Trn159_Val177.ipynb为IPRC的特征工程+lightgbm预测；

* Sub01_FS_AQI_Val2.848为AQI的特征工程+lightgbm预测；

