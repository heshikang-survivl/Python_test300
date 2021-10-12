# 例1：反转一个三位整数
#问题描述：反转一个只有三位数的整数
# 问题示例：输入number = 123，输出321；输入number = 900，输出9。
# 代码实现
class Solution:
    # 参数s：字符串列表
    # 参数offset：整数
    # 返回值：无
    def reverseInteger(self,number):
        hundred = int(number/100)
        ten = int(number%100/10)
        one = int(number%10)
        return 100*one+10*ten+hundred
#主函数
if __name__ =='__main__':
    solution = Solution()
    number = 489
    answer = solution.reverseInteger(number)
    print("原始数值：{}".format(number))
    print("转换后数值：{}".format(answer))
