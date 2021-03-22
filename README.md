## 批量下载深交所、上交所的公司年报

所有代码 在 `Python`环境中，`*.py`可以在 `edit in IDLE` 中运行 即可。

### 深交所

- 项目代码来自 [**python_down_szse_pdf**](https://github.com/1183468065/python_down_szse_pdf)

- 文件夹中有 `list.txt`，只需含有公司股票代码

- 下载后的文件形式是：

  > 000155川能动力：2019年年度报告.pdf

### 上交所

- 代码修改自 `https://blog.csdn.net/u013781175/article/details/96566376` （[link](https://blog.csdn.net/u013781175/article/details/96566376))

- 调用了外部的公司列表

- 在朋友的帮助下修改了循环函数

          year = year-3
          if year < year_3:
              break

- 下载后的文件以文件夹形式保存，但未含公司简称。修改未果