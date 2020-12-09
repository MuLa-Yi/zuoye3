# zuoye3
实验目的：
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
掌握面向对象的类设计方法(属性、方法)；
掌握类的继承用法，通过构造方法实例化对象；
学会使用super()，用于实例化子类；
掌握使用Object根类的toString()方法,应用在相关对象的信息输出中。

实验要求：
1.编写上述实体类以及测试主类（注意类之间继承关系的适用）
2.在测试主类中，实例化多个类实体，模拟学生选课操作、打印课程信息（信息包括：编号、课程名称、上课地点、时间、授课教师 等）；模拟学生退课操作，再打印课程信息。
3.（要求有实验目的、要求、过程、流程图、核心代码、注释、系统运行截图、编程感想等，分章节罗列，不能在实验报告中粘帖大段代码）

实验过程：
人员输入学生和教师的编号，姓名，性别，年龄（新增） 学生继承人员的函数和方法，增加了选课的中文提示；教师继承人员的函数和方法，加入判断语句进行教师教授课程区分。 系统负责系统主体框架，主要语句、语法为循环、输入和判断。 如：什么学生选什么课，首先用判断语句判断用户输入的是哪个学生，然后用循环语句进入选课环节，继续用判断语句判断该学生是否选课，已选课则用判断是否退课或退出选课系统，未选课则判断用户输入选择的是哪门课。然后进入已选课判断是否退课或退出选课系统。

核心代码： System.out.println("请输入选课/退课学生编号"); Scanner xueShengXuanTui = new Scanner(System.in); 
int xSBH = xueShengXuanTui.nextInt(); 
retry: for(int b=0;b<2;b++) if(keChengBianHao1 == 0)；
System.out.println("离散数学:101"); 
System.out.println("JAVA:102"); 
Scanner xuanKe = new Scanner(System.in); 
int xuanke = xuanKe.nextInt(); 
if(xuanke == 101){ keChengBianHao1 = 101; }
else if(xuanke == 102){ keChengBianHao1 = 102; }
else { System.out.println("请输入正确课程编号"); b = 0; break retry; } }
else if (keChengBianHao1 == 101 ||keChengBianHao1 == 102);
System.out.println("输入0后回车退出选课系统"); 
Scanner tuiKe = new Scanner(System.in); 
int tuike = tuiKe.nextInt();
if(tuike == 1){ keChengBianHao1 = 0; }
else if(tuike ==0){ break; }
else{ System.out.println("请重新进行选择课程"); b = 0; 
break retry; } } } }
else if(xSBH == 2)}
 retry: for(int b=0;b<2;b++)
 
 实验结果：
 
 实验感想：
 
