# 彻底清除 MySQL
**顽固的 MySQL**

## 第一步：
>打开文件资源管理器--> 此电脑 --> 点击鼠标右键 --> 找到管理(点击打开) -->进入计算机管理 

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429164234.png)
>找到计算机管理（本地）--> 点击服务和应用程序 --> 点击服务 --> 在里边找我MySQL

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429164638.png)
>点击MySQL --> 将服务状态改为停止 --> 点击应用 --> 点击确定 --> 关闭

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429164840.png)

## 第二步
> 打开文件资源管理器 --> 找到MYSQL的文件（一般在C:\Program Files (x86)）--> 将文件直接删除

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429165308.png)

## 第三步
> 找到（C:\ProgramData）这个文件夹(这个文件夹为OS(C:)盘里的隐藏文件夹，如果没有在查看中打开一下即可)
> --> 删除里边的MySQL文件夹

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429165945.png)

## 第三步
>打开命令提示符窗口 --> 输入 regedit 打开注册表编译器 --> 使用Ctrl+F搜索（MySQL）--> 删除其中的 imagePath

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429170125.png)


![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429170425.png)


![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429171725.png)


![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429171857.png)

## 第五步
>在程序和功能中将关于MySQL的软件全部卸载掉

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429172251.png)

## 第六步
> 打开打开文件资源管理器 --> 此电脑（鼠标右键打开属性）--> 点击高级系统设置 --> 点击环境变量 -->
> 找到系统变量中的path --> 点击进去 删除关于MySQL的一切环境变量

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429172710.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429172756.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429172837.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429173044.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210429173122.png)

这样子就将MySQL从你的笔记本上彻底的删除，并且不会影响第二次安装 MySQL
希望我的文章可以帮助到你 ♥ 下边是个人的微信公众号 里边还有关于技术类的小文章

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/qrcode_for_gh_3637457fbc25_258.jpg)