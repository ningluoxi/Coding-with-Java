> 引言 ：这个项目我以学习的角度进行补充和完善，力求把登录 + 注册做到最完美！！！

该项目适用于 学习完 基础的编程语法的同学进行进阶学习

# 【1】基于Java实现简易的 注册 + 登录 系统

非 **数据库** 实现！！！
### 一、项目分析
1. 基础菜单栏：主界面、登录界面，注册界面
2. 类的划分：测试类、pojo类（存放账号和密码的构造方法）、信息存储类（专门存储用户注册的信息类【用于登录验证】）
3. 业务逻辑分析：该项目主要实现两个功能，
	- 一个是注册，用户点击注册，则会跳转到注册界面，输入要注册的账号密码，输入完成跳转到登录界面
	- 二是登录：用户会直接跳转到登录界面，通过已有的数据进行匹配登录

### 二、界面设计
这个大家自行设计
1. 基础菜单栏
> 欢迎来到 xxx 系统  
1、注册  
2、登录  
3、退出  
请输入你的选择:  

2. 登录界面
> 欢迎来到 xxx 在线 系统  
请输入你的账号:  
*aaa*  
请输入你的密码:  
*bbb*  
恭喜你登录成功！！！  
..............  

3. 注册界面
> 欢迎来到注册界面  
请输入你的账号:  
*ada*  
请输入你的密码:  
*abc*  

### 三、代码实现
我这里存储数据用到的是列表（ArrayList）,每次运行代码的时候，原有的数据就会保留，新注册的信息就会删除

代码大家自行 clone 即可
