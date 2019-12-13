## 一个简易的时间模块，模仿了PHP的部分扩展，仅支持python3

安装：

```
pip install python-time
```

使用方法，例如：

```
from pytime import time
print(pytime.timestamps())
```
输出：

```
1576225887
```

提供的所有方法：

```
def timestamps():
    """
    返回当前整形的时间戳（UTC+8h）
    """


def microtime():
    """
    返回当前的微妙级别的时间戳（UTC+8h）
    :return:
    """


def time_format(timestamp=None, format="%Y-%m-%d %X"):
    """
    根据入参的时间戳和格式化一个时间戳(UTC+8h)
    默认当前时间戳
    """


def strtotime(format_time):
    """
    时间格式转换成时间戳。
    支持两种时间格式：
    1、YYYY-MM-DD hh:mm:ss
    2、YYYY/MM/DD hh:mm:ss
    """

def shift(time_type: str, timestamp: int=None):
    """
    获取指定时间的偏移量之后的时间戳,偏移量单位可以为days、weeks、months、years。例如：1 days、-3 days、5 months etc.
    默认当前时间
    返回时间戳
    """


def sleep(second: int):

```
