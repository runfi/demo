### use jquery mobile make somethings 
### 主要做的是功能。
#### **获得图书分类 查看图书信息** 

---
### 附带有php文件
### 有兴趣可以自成接口 另外数据文件在网盘
> #### [http://pan.baidu.com/s/1slVPqLB](http://pan.baidu.com/s/1slVPqLB)     chp2
---
#### 样式跟布局没有过分得讲究去做。。
#### 有后台功能带数据
#### 请求有接口
#### 图片是直接加载豆瓣的。
#### 需要在上网的情况下使用
#### 还有加了个小东西。音乐的播放。
#### 上下首没有增加只做了暂停跟播放
#### 推荐页面没做本地存储  因为推荐每次是随机的。做存储意义不大
#### 首页跟每次点击进去的详细分类页都是有做缓存的
#### 具体页面也没有本地存储
#### 因为它的id也许会很多
#### 那么怕是会拖慢加载速度

#### 样式没有直接使用jq moblie的。
#### 自己写了一些 大概只用了它的header跟footer(他们分别都是fixed了然后2em的) 比较好用就没改了
#### 有些bug直接隐藏了还没有完全解决

#### 需要上网需要上网！！！
#### 请求的接口在网上的！！！
#### error回调没有写！所以会一直有加载！！！而没有提示！！
----
#### 移动端处理自动播放无效果
#### 用了替代的点击body触发自动播放
---
#### 做成了一个单页应用。