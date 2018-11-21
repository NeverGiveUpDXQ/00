# 00
DAY 1 review
#以#或者连续的三个单/双引号开始以及结束 == 注释

#变量命名一般是数字/大小写字母【大小写不一样】/以及下划线
 #注意：数字不可以开头；一般下划线开头的有特殊意义，不推荐以其命名开头，推荐posix规则-多个单词之间用下划线并单词小写my_first_school
 #大驼峰MyFirstSchool
 #关键&保留词 ：class/break/def
  #如何查看系统中的关键词：
  import keyword #引入模块
  print(keyword.kwlist)#打印系统全部关键词
  
#变量声明
 #var_name = var_value
 #var1 = var2 = var3 = var_value
 #var1,var2,var3 = v1,v2,v3

#变量的类型
 #严格意义上，python只有一个类型
 #标准数据有六种：数字类型number/字符串类型str/列表list/元组tuple/字典dictionary/集合set
  #Number
    #整数 - 包括0
    #整数分进制
     #二进制 - 1.计算机常用 2.以0b开头的0，1代码
     #八进制 - 1.不常用 2.以0o开头包含0-7的数字
     #十六进制 - 1.其实是每四位二进制表示一位十六进制 2.以0x开头，包含0-9，a-f
     #十进制
     age = 18
     print(age)
     age1 = 0b10010
     print(age1)
     age2 = 0o22 #2*8的0次方+2*8的1次方 = 18
     print(age2)
    #浮点数float
     #小数
     #科学计数法 - 写法是用e/E后面跟整数表示10的整数 176.23 = 1.7623e2；0.876 = 8.76e-1
    #复数complex
     #定义和数学定义一致
     #一个由实部和虚部构成的数字
     #虚部用j/J表示 例如5+3j
     
     
