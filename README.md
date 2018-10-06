# sweep-mine
### 纯js实现简单的扫雷小游戏

#### 注意逻辑上：每次生成10 * 10的格子，随机生成10个雷，左键点击：如果是雷，10个雷全部显示出来，即给10个雷的格子背景换成“雷”的图片，如果不是雷，该给子周围的8个格子，是雷的数量，会显示在该格子上，如果该数字是0，即周围8个格子都不是雷，那么进行递归运算，周围8个格子，每个格子载进行一次“左键点击”事件，形成递归。
#### 只有当含有雷的格子都被右键旗子标记，同时，雷的剩余数量是0时，即成功的找出了所有的雷

### 失败的情况：
<img src = 'https://github.com/zhuyuzhu/sweep-mine/blob/master/images/fail.jpg' width=600 height=360 />

### 成功的情况：
<img src = 'https://github.com/zhuyuzhu/sweep-mine/blob/master/images/success.jpg' width=600 height=360 />
