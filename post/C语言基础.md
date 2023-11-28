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
    
  

二.数据类型，常量、变量及运算符

三.输入输出专题

四.控制语句

五.数组和字符串

六.指针

七.函数

