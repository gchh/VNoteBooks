# 第三章 数据和C
printf()函数要在打印的八进制、十六进制值前显示0和0x前缀，需要在转换说明中加入#。  

    int x=100;
    printf("dec=%d; octal=%o; hex=%x\n", x,x,x);
    printf("dec=%d; octal=%#o; hex=%#x\n", x,x,x);  
打印的结果是：  

    dec=100; octal=144; hex=64
    dec=100; octal=0144; hex=0x64
