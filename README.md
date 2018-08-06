# app

A Clojure library designed to build data pyramid.
## Usage

数据金字塔
可用来浏览海量数据

背景问题:
大数据量下,浏览器作为小窗口,显示海量数据有压力.做数据金字塔可来减少这种压力.

矛盾分析:
小与大的矛盾.(类似鸽巢,容斥原理)

解决思路:
小变大: 使用GPU加速
大变小: 构建数据金字塔

算法说明:
从根出发,逐级采样
最终是一棵树

对金字塔的访问就是对树的访问
## License

Copyright © 2018 FIXME

Distributed under the Eclipse Public License either version 1.0 or  any later version.
