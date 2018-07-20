# 第二章 C语言概述
C语言的基本模块是函数。  
C语言的语法错误是指，把有效的C符号放在了错误的地方。  
语义错误是指意思上的错误。如果遵循了C规则，但是结果不正确，那就是犯了语义错误。  
编译器可以检测出语法错误，但是检测不出语义错误。  
语义错误只有从程序运行中的行为表现出来。通过检查程序每执行一步变量值的变化，来确定语义错误。  
标识符，可以用大小写字母、数字和下划线_来表示；但是只能以字母或下划线开头。  
C语言有6种语句：标号语句、复合语句、表达式语句、选择语句、迭代语句、跳转语句。  
关键字是C语言的词汇，有特殊作用，不能用作标识符。  
加上C99和C11增加的关键字，C总共有44个关键字：  
void　char　int　float　double  
short　long　signed　unsigned  
enum　struct　union  
auto　register　static　extern　const　volatile  
sizeof　typedef  
if　else　switch　case　default  
do　while　for  
break　continue　goto　return  
_Bool　_Complex　inline　restrict　_Imaginary  
_Alignas　_Alignof　_Atomic　_Generic　_Noreturn　_Static_assert　_Thread_local  
