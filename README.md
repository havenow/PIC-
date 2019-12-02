- # Position Independent Code
问题由来：平台打的安卓target 26应用有arm汇编的模拟器无法运行

- # 有价值的链接

- # http://rss2.com/feeds/android-developers-blog/61/

![](https://github.com/havenow/PIC-/blob/master/pic/%E6%96%87%E6%9C%AC%E9%87%8D%E5%AE%9A%E4%BD%8D.png)

- # http://www.it1352.com/231224.html

![](https://github.com/havenow/PIC-/blob/master/pic/%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88.png)

- # https://www.cnblogs.com/alpine-enterprise/p/10897060.html

![](https://github.com/havenow/PIC-/blob/master/pic/pspax%E5%B7%A5%E5%85%B7.png)

查看那个函数有重定向问题，但是好像无法定位代码行数     
下面的命令是在Mac下面执行的     
/Users/wangf/Downloads/pax-utils-1.2.2/scanelf -qT /Users/wangf/Downloads/libmd.so 

- # https://wiki.gentoo.org/wiki/Hardened/Textrels_Guide#Introduction

讲了原理，但是修改的实例都是x86的汇编

LOCAL_LDFLAGS += -fPIC 对汇编无效果    

- # https://dev.gentoo.org/~vapier/dist/

工具下载

