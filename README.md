# Python Utils 项目



## 项目简介
> 目的是为了方便开发使用，因为在开发中有部分操作是完全重复的。

这是一个包含多个**Python** 实用函数的项目，提供了一些常用的工具类和函数，可以在多个项目中使用。





## 使用方法

在 **Python** 项目中导入需要使用的模块，例如：

```py
from utils import date_utils
```



调用模块中提供的函数或类，例如：

- 获取 **'2020-01-01'** ~ **'2022-01-01'**  获取 日期范围

```py
date_list = date_utils.get_date_range('2020-01-01', '2022-01-01')

# 输出
[
    datetime.datetime(2020, 1, 1, 0, 0), 
    datetime.datetime(2020, 1, 2, 0, 0), 
    datetime.datetime(2020, 1, 3, 0, 0), 
    datetime.datetime(2020, 1, 4, 0, 0),
    ...
    datetime.datetime(2021, 12, 31, 0, 0), 
    datetime.datetime(2022, 1, 1, 0, 0)
]
```



## 功能列表

此项目目前包含以下**Python**实用功能：

- `config_utils.py`：用于加载和解析配置文件的实用程序函数。
- `date_utils.py`：处理日期的工具类，如 **获取日期区间、获取日期差异、格式化时间** 等；
- `html_utils.py`：处理 **HTML** 内容的工具类，如 **获取标题、提取所有href链接、获取xpath标签节点** 等；
- `json_utils.py`：处理 **JSON** 数据的工具类，如 **读取、写入、添加、删除**等；
- `network_utils.py`：处理网络请求的工具类，如 **构建url、网络请求、上传文件、下载文件** 等；
- `string_utils.py`：处理字符串的工具类，如 **批量替换字符串** 等；


## TODO List
- [ ] `docx_utils.py`： word文档处理工具类，**提取文档内容** 等；
- [ ] `file_utils.py`：文件处理工具类，如 **复制文件、复制文件内容、移动文件** 等；
- [ ] `pdf_utils.py`： pdf处理工具类，如 **pdf转图片、提取pdf内容** 等；
- [ ] `photo_utils.py`： 图片处理工具类，如 **图片二值化、调整对比度、图片合成pdf** 等；
- [ ] `window_utils.py`： 窗口处理工具类，**最大最小化窗口、窗口指定、获取缩放比例** 等；
- [ ] ...


## 未来计划

我们计划继续添加新的实用程序函数和功能，以进一步增强此项目。



## 贡献

如果您想贡献代码或报告错误，请随时在GitHub上提交请求或问题。我们欢迎您的贡献！





****