           android 反编译

###1. 将apk后缀改为".zip",获取到classes.dex文件
  ![得到dex](https://github.com/2402091500/apkTojava/blob/master/1.png)
###2.用dex2jar这个工具来生成classes_dex2jar文件.
 * a,把刚刚解压出来的classes.dex文件放到dex2jar根目录，然后用dos命令定位到该目录，执行命令dex2jar.bat classes.dex直到done.
     ![得到dex](https://github.com/2402091500/apkTojava/blob/master/2.png)
 * b，在dex2jar根目录会多出一个jar文件
  ![得到dex](https://github.com/2402091500/apkTojava/blob/master/3.png)
 * c，用jd_gui.exe 就可以查看apk的目录结构了。
  ![得到dex](https://github.com/2402091500/apkTojava/blob/master/4.png)
  ![得到dex](https://github.com/2402091500/apkTojava/blob/master/5.png)