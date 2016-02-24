title: 处理1亿个QQ号
date: 2015-12-20 17:49:22
tags:
 - question
categories:
 - challenges
---
### 题目描述
   1. 请实现以下用于生成QQ号的函数。生成 1 亿个**乱序排列**且不重复的QQ号至 a.txt , 再生成 100 万个至 b.txt。注意：每个被选号码应是**等概率随机**抽取的。
   ```python
   def gen_qq_numbers(m, n, k, output):
      """
      用于生成QQ号的函数, 即[m, n]区间内k个不重复的等概率随机数。
      :param m: int, 所生成的QQ号须大于正整数 m, 大于等于10000
      :param n: int, 所生成的QQ号须小于正整数 n, 小于等于999999999
      :param k: int, 一共生成 k 个QQ号
      :param output: string, 文件名，生成结果保存至output中， 每行一个QQ号
      """
      # TODO
      pass
   ```

   2. a.txt 中有 1 亿个， b.txt 中有 100 万个乱序排列的QQ号。实现并、交、差运算， 并分别输出结果至union.txt, intersection.txt, difference.txt 。

### 题目要求
  1. 所有输入输出均以UTF8编码形式处理；
  2. 只允许使用CPython标准库和内置函数提供的方法、模块；
  3. 以上两小题都必须能运行出结果才有可能获得 "参考答案" 的殊荣；
  4. Python 版本仅限于 2.7 或 3.4+, 小版本号不限；
  5. 必须符合PEP8编码风格, 会进行编码风格检查.

### 评比规则
  生成一次1亿个QQ号，交并差运算各执行一次，就算一遍完整的运行， 三遍完整的运行时间平均值用于评比。基本规则请参考“帮助”页面中的“评比规则”。

### 提交答案
   参考 “帮助” 页面
