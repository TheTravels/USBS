# USBS
多年前通过模拟USB存储设备制作的 bootloader，带加密机制，通过擦出加密代码保证加密过程只执行一次

目录：

-| 

 |- Qt ：Qt上位机
 
 |- Release   : 发布代码，移植文档移植过程中的代码
 
 |- USBS_20150619_对USBS升级 ：通过app升级 bootloader
 
 |- USBS_F4 ：F4移植文档
 
 |- encrypt.c 采用写0(或写1)方式实现的加密
 
 |- tea.c tea加密算法
 

关于最新 encrypt.c中加密的详细说明可查看[仅使用对 flash的写操作实现加密代码的自擦除](https://github.com/Merafour/Bootloader/wiki)。
