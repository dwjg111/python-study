# Python 学习笔记

> 从 2026 年 8 月开始，跟着黑马程序员《Python+AI 零基础入门到大神》学习。


## 每日流程
1. 学完写代码（lessonXX.py）
2. 更新 notes.md
3. git add . -> git commit -m "第X课" -> git push

#

# 第二章小结
-空值   None   
-int   -float   -str   
-bool:  Ture    False

### 第二章：数据储存和运算
**09**  
- 字面量：固定值    
- 变量  ：不用定义数据类型 num = 3.14,  
        可以连续赋值，a,b = 1,2  
        print(a,b,c)  
  - 标识符：变量，函数，类    名。  严格区分大小写，数字不能开头  

常见数据类型：  
type()  
isinstance(数据，类型)--->bool值
  
字符串：  
- 单引号，双引号，  ：不可换行  
- 三引号：（多行字符串）  
        """你  
         好 """

转义字符：  \  
- \\': 单引号 
- \\": 双引号 
- \\n: 换行符
- \\t: 制表符 tab:  

字符串拼接：  
- "+"号可以拼接两个字符串或者字面量（非字符串类型需要转换为字符串类型）  
- str( )    ； 强制转string  
- int( )
- float( )
- bool( )


- 占位符：%s  
name = "xiao"  
age = 10  
pro = "software engineering"  
hobby = "python"  
print("my name is %s, I am %s, study %s, my hobby is %s" % (name, age, pro, hobby))  4


- **f"内容{变量、表达式}"**     (企业开发推荐）  
name = "xiao"  
print(f"my name is {name }")  
  
/n

**输入与输出**  
- **input**  
- input (提示)  // 获取到的都是字符串类型  
name = input("请输入你的姓名：")  
print(f"my name is {name}")  


算术运算符：  
+ 加 - 减 * 乘 / 除  除法结果一定是float  
// 整除 % 取余 ** 幂指数   

赋值运算符  
- = += -= %=

比较运算符  
返回布尔值  Ture False  
== != > < >=  
  
逻辑运算符  
and or not 
  
#

### 数据逻辑处理
   



#

#  /

## 学习计划
- 目标：8 月学完核心语法部分（约前 87 集），9 月前能独立写小程序
- 每天：2-3 集 + 自己敲代码 + 记录报错

# /

## 每章小结
（学完一章，用自己的话写 3-5 行，写不出来说明没懂，回去再看）

### 第 X 课：课程名
- 讲了什么：
- 我学到的新东西：
- 


## 报错记录
（格式：报错信息 → 原因 → 解决方法，遇到就记，积累排错经验）

| 日期 | 报错信息 | 原因 | 解决方法 | 源代码 | 更正后代码 |
| --- | --- | --- | --- | --- | --- |
| 2026-08-07 | NameError: name 'x' is not defined | 变量还没赋值就使用 | 先给变量赋值再使用 | `print(x)` | `x = 1`<br>`print(x)` |
| 2026-08-07 | SyntaxError | 少了一个冒号 | 检查行尾加上冒号 | `if 1 == 1 print("ok")` | `if 1 == 1: print("ok")` |

