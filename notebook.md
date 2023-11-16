# 熟悉Git版本控制系统的使用

### 代码仓库初始化

初始化就是在Github里面创建一个新仓库（new repository)

![image-20231116102033344](D:\大学\大三上\cloud_calculation\Alkaid3118\img\image-20231116102033344.png)

然后给仓库命名，记得Add a README file

### 了解git  clone、git commit 等基本操作

- #### git clone操作

  1. 找到仓库的SSH并复制

     ![fc078e2d144b6a0b6f673207b8f3ed0](D:\大学\大三上\cloud_calculation\Alkaid3118\img\fc078e2d144b6a0b6f673207b8f3ed0.png)

  2. 如果我们想要把仓库内容拷贝到某个根目录下，举例如cloud-calculation文件夹，只需要右击cloud-calculation文件夹然后点击git bash here，然后git clone ssh的内容即可（右键paste)，就从GitHub上将这个仓库文件夹拷贝到cloud-calculation文件夹中了。

     ![image-20231116102903281](D:\大学\大三上\cloud_calculation\Alkaid3118\img\image-20231116102903281.png)

- #### git commit操作

  1. 右击仓库名的文件夹git bash here
  2. git add（空格）.
  3. git commit -m "提交信息"（此时本地仓库内容已缓存）
  4. 此时再git push就更新到GitHub上对应的仓库了

### 在Git中设置提交者身份（username和email等），了解基于提交者身份的代码溯源方法

git设置提交者身份是在一开始时就设置的，username和email，可以用git config --global --list命令查看全局配置。

![7a8701660a57237fbd5d936a626e0fe](D:\大学\大三上\cloud_calculation\Alkaid3118\img\7a8701660a57237fbd5d936a626e0fe.png)