# SSM：spring + springMVC + mybatis
# 面向对象编程：
    类/对象、类的结构、三大特征、接口、设计模式
# java特点：
    1、面向对象   基本概念(类、对象） 三大特性（继承、封装、多态）
    2、健壮性   3、跨平台性(依赖不同系统的JVM：java虚拟机)
# 基础类型有8种：
	  byte、boolean 8位（1字节）、char、short、int 32位（4字节）、float、long、double
# jdk  
	JDK = JRE + java开发工具
	JRE = JVM + java核心类库
    bin：开发工具  db：数据库  jre：java运行环境  lib：jar包
# 文本注释
  	 /** 
  	    @author ...  
   	   @version  ...
   	   内容
 	  */
 	  javadoc -d 文件夹名 -author -version 程序名
# 1
	在一个源文件中可以声明多个class，但是最多只能有一个为public修饰，声明为public的类的类名必须与源文件名相同
	main()方法为程序入口，格式固定   public static void main（String[] args）{}
# 标识符(必须遵守，否则无法编译)
	凡是可以自己命名的都叫标识符，例如类名、方法名、包名等
	严格区分大小写，不可以数字开头，不能包括空格
# java中命名规则(若不遵循，可以编译，但是建议遵循)
	包名：所有字母小写 aaabbbccc
	类名、接口名：每个单词首字母大写，其他小写 AaaBbbCcc
	变量名、方法名：多单词组成时，第一个单词全小写，之后单词首字母大写 aaaBbbCcc
	常量名：所有单词大写，多单词组成时，用下划线连接 AAA_BBB_CCC
	
