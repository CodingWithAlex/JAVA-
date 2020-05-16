# Java-Conclusion  
---
简介
----
>&#160; &#160; &#160; &#160;Java具有简单性、面向对象、分布式、健壮性、安全性、平台独立与可移植性、多线程、动态性等特点，Java可以编写桌面应用程序、Web应用程序、分布式系统和嵌入式系统应用程序等， 现对java相关知识点做相关总结。
    
2020.5.16更新
------
###内置包装类    
1.Object类  
>&#160; &#160; &#160; &#160;Object类是Java中所有类的父类，主要常用的方法有equals()方法,getClass()方法，其中equals()用于比较两个对象内容是否相等（==是比较地址）；而gerClass()方法用于返回该类的各种信息包括类名（getName()），父类（getSupperclass()）及所实现接口（getInterfaces()）的名字。  

2.Integer类  
>&#160; &#160; &#160; &#160;Integer类在对象中包装了一个基本类型int值。Integer类对象包含一个int类型字段，提供int类型和String类型之间的转换。int类型转String类型（Integer.parseInt(str)）,String类型转int类型（Integer.toString(int)）。  

3.Double类
>&#160; &#160; &#160; &#160;Double类在对象中包装了一个基本类型double的值。Double类对象包含一个double类型字段，提供double类型和String类型之间的转换。double类型转String类型（Double.parseDouble(str)）,String类型转double类型（Double.toString(double)）。  

4.Number类
>&#160; &#160; &#160; &#160;Number类是一个抽象类也是一个超类（父类），属于java.lang包。所有的包装类（如Integer类，Double类等）都是抽象类Number的子类。Number定义了一些抽象方法以各种不同的数字格式返回对象的值。__抽象类不能直接实例化，而必须实例化具体的子类__。


