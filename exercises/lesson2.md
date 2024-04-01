
1. 编译成内核模块，是在哪个文件中以哪条语句定义的？

kbuild的make

```
obj-m := r4l_e1000_demo.o
```

2. 该模块位于独立的文件夹内，却能编译成Linux内核模块，这叫做out-of-tree module，请分析它是如何与内核代码产生联系的？

  1. f
