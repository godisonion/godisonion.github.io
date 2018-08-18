---
title: 《C++ Primer》读书笔记 - 1.4.3
date: 2018-08-13 21:43:39
categories: C++
---
## 1.
```bash
while(std::cin >> value)
	sum += value;
```
读入的值用空格或换行符分隔，当遇到输入为文件结束符或者无效输入时（此处如果输入的数不是整数即无效输入），istream对象的使while条件为假。