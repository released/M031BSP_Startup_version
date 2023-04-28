# M031BSP_Startup_version
 M031BSP_Startup_version


update @ 2023/04/28

1. refer below sample code , to add version control in startup.s

http://forum.nuvoton.com/viewtopic.php?f=19&t=8349&sid=773e58eb8722b1de11c21ba0de276b8c

2. Copy startup.s to a new one to add version num.

![image](https://github.com/released/M031BSP_Startup_version/blob/main/add_new_startups.jpg)	



open startup.s and add version num.

![image](https://github.com/released/M031BSP_Startup_version/blob/main/modify_startups.jpg)	



modify startup.s name in KEIL option > Linker

![image](https://github.com/released/M031BSP_Startup_version/blob/main/modify_option_linker.jpg)	



below is the log , when MCU power on , read the content from startup.s 

![image](https://github.com/released/M031BSP_Startup_version/blob/main/log.jpg)	

