# aiofetch

建议使用Python3.7，其他版本没有测试过，无法保证兼容性

本爬虫是异步多进程爬虫，高效易用，扩展方便

建议本地自建存储，不要给知乎的服务器造成过多不必要的压力

一次爬太多会被问验证码，遇到HTTP错误不会停止

建议分批次爬，每批次的`task_count`控制在100K以内

使用示例在`data_getter.py`中的`if __name__ == '__main__':`中，比较简单，也有工地英语注释，文档就不写啦

部分API无需cookie，但默认全部使用cookie模拟登陆

如有个性化需求，可以直接修改源码

欢迎走过路过的看官提出任何建议~

觉得还行请star~

知乎[@stringstrange](https://www.zhihu.com/people/.people./activities).
