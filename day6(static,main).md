![Alt text](image/day6/image.png)

![Alt text](image/day6/image-1.png)

![Alt text](image/day6/image-2.png)

类变量=静态变量

jdk 1.8以前静态变量是放在方法区的静态域中，jdk 1.8以后静态变量在堆里面。

![Alt text](image/day6/image-3.png)

1. 类变量是所有对象所共享的。
2. 类变量在类加载时就创建了。
3. 类变量依然遵守访问权限。

![Alt text](image/day6/image-4.png)

![Alt text](image/day6/image-5.png)

![Alt text](image/day6/image-6.png)

![Alt text](image/day6/image-7.png)

类方法和普通方法都是随着类加载而加载，将结构信息储存在方法去，类方法中无this的参数，普通方法中隐含着this的参数。

![Alt text](image/day6/image-8.png)

![Alt text](image/day6/image-9.png)

![Alt text](image/day6/image-10.png)