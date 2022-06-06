# FigureBest v4 帮助文档 Documentation of FigureBest v4
![](images/FBV4-公众号封面图.png)

## 1. 简介 Brief introduction

## 2. 常见问题 General questions

### 如何对Simulink模块的图进行美化？

处理Simulink图的核心思想是**重绘**（RePlot），即，一键绘制一份能够被FB处理的副本。FB不一定能美化所有工具箱的图，因为各个工具箱差别巨大，以**Scope**图为例：

- 第1步：从工具箱导出.fig图，各个工具箱差别很大，但是基本都有该功能;
![](images/scope-1.png)
![](images/scope-2.png)

- 第2步：使用FB上的**RePlot**按钮自动生成一份FB可以处理的副本（在FB4.3上位置如图所示）;
![](images/scope-3.png)
![](images/scope-4.png)

- 第3步：输入对应的左上角.fig编号进行美化，像普通的.fig图一样;
![](images/scope-5.png)

### 为什么点美化后标签中中文变成了乱码或者方框？

美化是针对SCI英文环境的图，所以美化的时候无论用户设置什么字体，都会修改为**Times**字体，一般来讲这是高效且直接的。如果原来有中文字体，中文字体与Times不兼容，会发生冲突，变成方块或者乱码，只要点击**中文**按钮，或者自己修改成中文字体即可恢复。（注意：MATLAB一个文字框只能包含一种字体，既有英文的Times又有中文是做不到的）

![](images/chaoOfChinese-1.png)

![](images/chaoOfChinese-2.png)

### 3. 功能3

### 4. 功能4

