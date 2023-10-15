# 搜呼社工库 By huoji 2010年的作品
 ![image](https://github.com/huoji120/Huoji_Sohu_Project/blob/master/2-1.jpg)
 ![image](https://github.com/huoji120/Huoji_Sohu_Project/blob/master/2.jpg)
 ![image](https://github.com/huoji120/Huoji_Sohu_Project/blob/master/3.jpg)
  # -
搜呼社工库源代码
/huoji/* 下的文件是会员登陆注册、在线工具所用到的文件
/huoji/config.php 是登陆注册所用到的数据库链接文件
/huoji/tools.php 是在线工具,未开发完毕.
index.php 是主要文件
1.设置好coreseek
2.修改index.php里面的数据库配置
3.修改/huoji/config.php里面的配置(建议使用不同数据库,或者不同表)
4.为用户登陆注册建立字段 字段分别是 username email password
登陆和注册 密码操作那里加个md5() 否则密码会明文储存.