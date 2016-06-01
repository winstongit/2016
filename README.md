# 2016 0601 start
一samba代码权限保护问题

1.重启
service smbd restart

2.samba的权限控制
不能访问系统的其他区域
windows下确实不能访问
Linux下确实也不能访问

[winston]
   comment = winston
   browseable = yes
   path = /home/winston
   guest ok = no
   writeable =yes
   create mask = 0755
   read only = no
   public    = no
   vaild users = winston

二对数据的打包


三对客户问题的分析
1- when you start the box not playing any channels you need change channels to open channels

2- when you see tv, only SD channels the image frezze and the audio working

