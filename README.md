# CV_Competition
CV 赛题学习之科大讯飞新人赛人脸关键点检测挑战赛 

比赛地址：https://challenge.xfyun.cn/topic/info?type=key-points-of-human-face&ch=dw-sq-1

打卡地址：https://shimowendang.com/docs/XkpH6d8pHRgCtgV8/read
## 打卡任务1
报名比赛，下载比赛数据集并完成读取

```python
import pandas as pd
import numpy as np
# 读取数据
train_df = pd.read_csv('data/train.csv')
train_img = np.load('data/train.npy')
test_img = np.load('data/test.npy')
# 对数据集样本进行可视化，统计关键点坐标分布

```
