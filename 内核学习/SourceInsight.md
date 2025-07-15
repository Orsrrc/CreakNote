这主要是通过SourceInsight查看WRK的一个源码



WRK -v1.2

SourceInsight.exe 安装 输入给的序列号

![image-20250714201924349](./SourceInsight.assets/image-20250714201924349.png)![image-20250714202735335](./SourceInsight.assets/image-20250714202735335.png)

任意创建一个工程

![image-20250714202801986](./SourceInsight.assets/image-20250714202801986.png)

打开WRK的目录，将其中的源代码全部添加到项目树中

![image-20250714202837873](./SourceInsight.assets/image-20250714202837873.png)

![image-20250714202908687](./SourceInsight.assets/image-20250714202908687.png)

成功加载

![image-20250714202927502](./SourceInsight.assets/image-20250714202927502.png)

搜索要查看源码的API

![image-20250714202947005](./SourceInsight.assets/image-20250714202947005.png)

查看项目中有哪一个函数调用了它

![image-20250714203015182](./SourceInsight.assets/image-20250714203015182.png)

![image-20250714203044027](./SourceInsight.assets/image-20250714203044027.png)



- 单机 查看哪一个函数调用该函数

- 双击 查看调用函数的代码

- Shift + F8 高亮显示某一串字符