对[《手把手教你构建 C 语言编译器》](https://github.com/lotabout/write-a-C-interpreter)的学习。

```
gcc xc-learn.c -o xc-learn.exe
.\xc-learn.exe hello.c

.\xc-learn.exe xc-learn.c hello.c
.\xc-learn.exe xc-learn.c xc-learn.c hello.c
```

`calculator.c`为《手把手教你构建 C 语言编译器（4）- 递归下降》示例代码，其中用到的函数`getline`，在`getline.c`中实现。