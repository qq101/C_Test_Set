#####题目：旋转数组的最小数字
#####描述：
把一个数组最开始的若干个元素搬到数组的末尾，我们称之为数组的旋转。输入一个非递减序列的一个旋转，输出旋转数组的最小元素。例如数组{3,4,5,1,2}为{1,2,3,4,5}的一个旋转，该数组的最小值为1。
#####值得关注点：
1. 两种解题思路：
    + vector中存在两个有序子序列，第一个有序子序列的最小值一定是第一个元素min，只要找到比min小的元素即可
    + 利用set的特性（元素内部有序）
2. 关于容器set的操作：
    + 见代码中
 3. **用for，while循环语句操作顺序容器时（利用下标或迭代器），都会碰到段错误**
    - 暂时的想法：
        - 编写代码前，先将边界情况考虑清楚；
        - 将首尾的迭代器或元素拷贝出来进行操作。