##### 题目：调整数组顺序使奇数位于偶数前面

##### 描述：
输入一个整数数组，实现一个函数来调整该数组中数字的顺序，使得所有的奇数位于数组的前半部分，所有的偶数位于位于数组的后半部分，并保证奇数和奇数，偶数和偶数之间的相对位置不变。
##### 注意事项：
1. 解法1：利用另一个数组，按奇偶个数顺序插入；空间换时间
2. 解法2：利用指针操作，循环遍历array；类似冒泡法：将奇数一个个往前冒