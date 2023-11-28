  一.linux命令和C语言基础
  1.查看ubuntu版本：cat /etc/issue
  2.linux文件系统：linux文件系统是一个蜀兴分层组织结构。/bin存放二进制文件和命令、/boot存放系统启动时要用到的程序、/dev代表linux要用到的外部设备、/etc表示系统管理时用到的配置文件和子目录、/lib存放系统动态连接的共享库、
    /home普通用户主目录、/root根用户主目录
  3.shell命令：ls -R ：递归显示所有目录及子目录、pwd、cd、cat a.txt：将内容打印到终端；
    cat -s：空行合并、cat(nl) -b：添加行号显示、head -n：显示文件的前n行、tail -n:显示文件的后n行(默认10行)；
    cp -r、cp -i是否覆盖、mv（移动/重命名）、touch、rm -r、mkdir -r：级联创建
  4.vi编辑器的使用：
    三种模式：命令行模式、底行模式、插入模式。ESC命令行模式、插入模式：i a s o I A O
    命令：nyy、ndd、p、P、np、nP、q、w、wq、!q、vsp分屏
      gg：行首、G：行尾、dG：删除光标以后内容、:n：跳转到第n行
      vi 文件名 行号：跳转指定行、ctrl+w h 跳到左边窗口、ctrl+w l 跳到右边窗口
  5.文件类型：
  .c：C语言源代码、
  .h：程序所包含的头文件、
  .i：预处理过的源代码文件、
  .s汇编语言源代码文件、
  .o：编译过后的目标文件，等待链接
二.数据类型，常量、变量及运算符
  1.数据类型分类：
  -基本数据类型：（double和long long是8字节）
    整型：short、int、long(64位机下位8字节)
    字符型：char
    实型：float、double
    枚举：enum
  -构造数据类型
    数组
    结构体struct
    共用体union
  -指针类型
  -空类型void
2.基本数据类型：
  -逻辑型：bool 1字节
  -整数类型：char、short、int、long
  -浮点型：float、double（浮点型不能做除法和取余运算）
3.常量
  -不可改变的量，#define 标识常量名称
4.变量
  -变量的命名：由字母数字下划线组成，不能以数字开头，不能和关键字重名
  -变量的存储类型：auto（默认），static，register，extern
    auto：局部变量，可省略，初始值不确定
    static：（default 0）
      全局变量不能引用在其他文件中，减小作用域
      局部静态变量：存放在内存用户空间的数据段，没有存储在堆栈中
    registerr：寄存器变量
      因寄存器是有限的频繁访问的变量可用此类型

三.输入输出专题

四.控制语句

五.数组和字符串

六.指针

七.函数

