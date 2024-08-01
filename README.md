# 资治通鉴-文白对照-文本数据

## 文白对照阅读
[阅读书籍点击](https://jy0284.github.io/zizhitongjian/)

## 简介
项目地址：[zizhitongjian](https://github.com/JY0284/zizhitongjian)

这个仓库是有关**资治通鉴-文白对照**的可供**人类和机器阅读阅读**并进行**相关数据研究**的项目。

本项目中的文本格式按照原书的`卷`进行整理，`chapters`目录下按照`[0-9]+_资治通鉴卷名.md`进行分别存储：

```shell
chapters
├── 001_资治通鉴第一卷(周纪).md
├── 002_资治通鉴第二卷(周纪).md
├── 003_资治通鉴第三卷(周纪).md
...
```

每一卷的内容格式如下（`*`表示在部分卷中可能不存在的内容）：

```python
[卷名]*

[时间原文]
[时间译文]

[空白][空白][原文]
[空白][空白][译文]

[空白][空白][原文]
[空白][空白][译文]

[时间原文]
[时间译文]

[空白][空白][原文]
[空白][空白][译文]
```

## 项目进展

项目在持续更新，目前任务列表完成情况如下：
- [x] 文本内容获取
- [x] 格式化卷名，便于排序及查询
- [x] 时间数据的译文格式保持和原文格式统一
- [x] 去除不符合文白对照格式的空行、空格，使用统一的换行格式
- [x] 文本内容程序化校对，定位残缺和错误内容
- [ ] 文本数据结构化，便于利用数据分析工具和可视化工具进行处理
- [ ] ...

数据预处理的部分源码及说明在本项目的`*.ipynb`中存档及更新。

## 参与贡献

1. 请在issue中提供任何意见建议，不限于文本内容、文本格式、数据结构、数据分析、数据可视化等任何主题；
2. 文本中有`[todo]`的地方为分析过程中发现的内容残缺的部分，可以参与校对和修复:D

## 相关资源
1. http://www.ziyexing.com/files-5/zizhitongjian/zizhitongjian_index.htm
2. https://ctext.org/wiki.pl?if=gb&res=548761&remap=gb
3. 卷28译文可参考：http://www.ziyexing.com/files-4/yywj-157.htm


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=JY0284/zizhitongjian&type=Date)](https://star-history.com/#JY0284/zizhitongjian&Date)
