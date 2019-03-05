## 开发中常用的一些工具类
```
git remote add origin https://github.com/JHiroGuo/Tools.git
git push -u origin master
```



### iOS/MacroDefinition.h 
    增加IOS中常用的宏定义

### macOS/JHLabel
##### 简述：
	在Mac OS X上实现UILabel的主要功能。与NSTextField相比，占用内存和CUP消耗更小，完美的像素呈现。
##### 使用需求
	ObjC 2.0和自动引用计数(ARC)。
	Xcode6+，最低在Xcode6上测试过，不知道是否适用于更旧版本
##### 依赖关系
	除了Cocoa框架之外，没有其他依赖项。
##### 使用
引入JHLabel.h 。像UILabel类那样使用它。但是请记住，并不是所有特性都受支持。有关当前属性的更多信息，请参见头文件。
