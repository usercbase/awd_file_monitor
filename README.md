## 说明

文件监控，用来监控py文件以及其子目录下的所有文件的增删改

此脚本基于https://gitee.com/piri47/AWD-1/blob/master/%E6%96%87%E4%BB%B6%E7%9B%91%E6%8E%A7.py  

如有侵权，请联系删除

做出的改进：

* python2和python3各一版本，亲测都可用
* 调用的都是python自带库，不用额外安装其他库
* 不会删除原文件，避免因为某些意外情况而导致的原文件被删除
* 前端打印所有详细信息，包括文件路径、被修改的时间、内容等

python2请使用monitor-py2.py

用法

```
python2 monitor-py2.py
```

python3请使用monitor-py3.py

用法

```
python3 monitor-py3.py
```
