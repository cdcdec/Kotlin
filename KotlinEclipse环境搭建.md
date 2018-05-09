## KotlinEclipse环境搭建﻿

1. Eclipse 通过 Marketplace 安装 Kotlin 插件，打开 Eclipse，选择 Help -> Eclipse Marketplace… 菜单，搜索 Kotlin 插件，根据提示安装
2. 然后重启 Eclipse 选择 Window -> Open Perspective -> Other...，如果看到了 Kotlin 选项表明安装成功。



#### 创建新项目

1. 选择 File -> New -> Kotlin Project 来创建 Kotlin 项目：

2. 点击 src 文件夹，创建一个包com.cdc.kotlin,并在这个包里面创建一个kotlin文件,名称为Hello,不用写 ".kt" ，默认自动添加。

3. 在 Hello.kt 文件中写点代码。Eclipse 为我们提供了一个快速完成此操作的模板，只需键入 main 然后按 Enter 即可。

   ```
   package com.cdc.kotlin
   fun main(args: Array<String>) {
   	println("Hello world")
   	println("Kotlin")
   	print("!")
   }
   ```

4. 在Hello.kt 的编辑框内右击鼠标选择 Run As -> Kotlin Application 即可运行





#  在Eclipse里面新建Gradle工程，在此工程里面使用Kotlin没有配置成功