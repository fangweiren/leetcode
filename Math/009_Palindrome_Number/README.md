#思路

1.负数没有回文数

2.得到x是几位数，如x=12321,得到count=10000

3.然后分别判断最左边一位和最右边一位是否相等

4.x去掉左右一位，先对count取余再除以10，而count则缩小100倍