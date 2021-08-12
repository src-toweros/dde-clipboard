# dde-clipboard

#### 介绍
剪贴板展示当前用户登录系统后复制和剪切的所有文本、图片和文件。使用剪贴板可以快速复制其中的某项内容。注销或关机后，剪贴板会自动清空。

#### 软件架构
软件架构说明


#### 安装教程

1. [下载](https://openeuler.org/zh/download/)openEuler ISO镜像并安装系统

   ```
   https://openeuler.org/zh/download/
   ```

2. 更新软件源

   ```
   sudo dnf update
   ```

3. 安装DDE

   ```
   sudo dnf install dde
   ```

4. 设置以图形界面的方式启动

   ```
   sudo systemctl set-default graphical.target
   ```

5. 重启

   ```
   sudo reboot
   ```

6. 在重启完成后，使用安装过程中创建的用户或openeuler用户登陆桌面

   ```
   dde桌面无法使用root账号登陆 dde内置了openeuler用户，此用户的密码为openeuler
   ```

#### 使用说明

1. 使用快捷键 **Ctrl** + **Alt** + **V** 唤出剪贴板。
2. 双击剪贴板内的某一区块，会快速复制当前内容， 且当前区块会被移动到剪贴板顶部。
3. 选择目标位置粘贴。
4. 鼠标移入剪贴板的某一区块，单击上方的**X**，删除当前内容；单击顶部的**全部清除**，清空剪贴板。



#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
