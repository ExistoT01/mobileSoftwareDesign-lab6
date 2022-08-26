# 2022年夏季《移动软件开发》实验报告

<center>姓名：叶鹏  学号：20020007095</center>

| 姓名和学号         | 叶鹏，20020007095                                            |
| ------------------ | ------------------------------------------------------------ |
| 本实验属于哪门课程 | 中国海洋大学22夏《移动软件开发》                             |
| 实验名称           | 实验6：安卓APP首页                                           |
| 博客地址           | [Click me if you can](http://existot01.top/)                 |
| Github仓库地址     | [You won't miss that](https://github.com/ExistoT01/mobileSoftwareDesign-lab6) |

（备注：将实验报告发布在博客、代码公开至 github 是 **加分项**，不是必须做的）



## **一、实验目标**

- ScrollView 使用
- RelativeLayout 使用
- 插件之间的穿插使用

## 二、实验步骤

列出实验的关键步骤、代码解析、截图。

1. 项目创建

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003088.png" alt="image-20220825231548836" style="zoom:80%;" />

2. 新建`ScrollView`，确定内部父布局

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003090.png" alt="image-20220825231733462" style="zoom:80%;" />

3. 创建顶部首页显示栏，调整相关参数

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003091.png" alt="image-20220825232046151" style="zoom:80%;" />

4. 创建顶部图片，修改相关参数

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003092.png" alt="image-20220825232316896" style="zoom:80%;" />

5. 实现菜单栏模块

   1. 先实现一个横向的`LinearLayout`作为父布局

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003093.png" alt="image-20220825232828332" style="zoom:80%;" />

   2. 写4个子布局

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003094.png" alt="image-20220825233545402" style="zoom:80%;" />

6. 消息模块

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003095.png" alt="image-20220826002317977" style="zoom:80%;" />

7. 两条消息内容

   1. 新建一些颜色圆角形状备用

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003096.png" alt="image-20220826095841639" style="zoom:80%;" />

   2. 创建消息卡片

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003097.png" alt="image-20220826095959566" style="zoom:80%;" />

8. 底部Tab模块，采用相对布局

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003098.png" alt="image-20220826100024508" style="zoom:80%;" />

   





## 三、程序运行结果

列出程序的最终运行结果及截图。

<img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208261003099.png" alt="image-20220826100100506" style="zoom:80%;" />

## 四、问题总结与体会

本次实验仿照其他安卓app简单写了一个首页界面，练习了相对布局的用法，`ScrollView`的作用在本实验体现出来的地方不大，而且`tabBar`也不具有吸底的效果，安卓的开发在很大程度上要比小程序的开发复杂得多

