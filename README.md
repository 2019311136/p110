# p110
实验目的
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
掌握面向对象的类设计方法（属性、方法）；
掌握类的继承用法，通过构造方法实例化对象；
学会使用super()，用于实例化子类；
掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。
实验过程
先创建人员(Human) 类,输入编号.姓名、性别，后创建人员的子类:老师、学生,
使用super用法继承编号、姓名性别，
然后构造老师、学生所对应的课程,后创建课程类,构造课程的编号、名称、地点、时间、教师，
最后创建主类Text输入老师学生课程所对应的名称,然后进行输出。
核心方法.
public Personnelint number,String name, String sex){ this.name = name; this.number = number; this.sex = sex;
System.out. println("编号:" + number +“姓名:" + name + "性别:" + sex); } super(number,name,sex); Map<String, Boolean>map= new HashMap< String,Boolean> 0;
实验结果
姓名：cizen性别：male
姓名：Lu性别：female
所选课程大学视听说选课成功大学视听说
实验感想
通过这次实验，我学会了如何用super语句让子类继承父类的构造方法;
在构造数组时遇到了困难，使用了map语句进行映射;反复尝试后学会利用void并设立无参数解决,并初步了解了选课系统的构造。
