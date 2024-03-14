# VerifyBookSource

阅读书源校验工具v3

## 项目

运行要求：

我用的是Python3.10

其他版本应该也没有问题，我并没有使用一些很新的语法。

原理：

其实是检验书源的网址能不能打开，至于其搜索能不能返回正确结果，还没有去实现。

## 功能

1. 自定义运行线程：线程越多就越快，但也不介意太多，容易将有效书源判断为无效书源。
2. 文件支持本地文件和文件直链
3. 支持重复书源去重
4. 自定义输出文件路径
5. 在原基础上增加检测wap类型站点
运行效果：
python app.py
欢迎使用书源校验工具（VerifyBookSource v2.0）
原作者：勿埋我心 - SkyQian
Github：https://github.com/Qiantigers/verifyBookSource
我的博客：https://www.skyqian.com
musa：https://github.com/asdf1319964f/checkbook
----------------
是否使用config.json文件？（不使用则通过命令行输入配置）（y/n）n
本地文件路径/文件直链URL：https://xiao.ml/shuyuan/7
书源输出路径（为空则为当前目录，目录最后带斜杠）：
请输入工作线程，填写数字（并不是越大越好）：64
是否去重？（y/n）y
----------------
检验进度：
[####################]100.00%
----------------
成果报表
书源总数：1444
有效书源数：736
无效书源数：708
重复书源数：0
耗时：43.06秒

输入任意键退出……
```
