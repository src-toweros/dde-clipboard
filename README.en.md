# dde-clipboard

#### Description
The clipboard displays all text, pictures and files copied and cut after the current user logs in to the system. Use the clipboard to quickly copy an item. After logging off or shutting down, the clipboard will be emptied automatically.

#### Software Architecture
Software architecture description

#### Installation

1. Download Openeuler ISO image and install the system

   ```
   https://openeuler.org/zh/download/
   ```

2. Update software source

   ```
   sudo dnf update
   ```

3. Install DDE

   ```
   sudo dnf install dde
   ```

4. The settings are started as a graphical interface

   ```
   sudo systemctl set-default graphical.target
   ```

5. restart

   ```
   sudo reboot
   ```

6. After the restart is completed, login to the desktop using the user created during the installation or openeuler user

   ```
   DDE desktop cannot login with root account. DDE has built-in openeuler user whose password is openeuler
   ```

#### Instructions

1. Use the shortcut keys **Ctrl** + **Alt** + **V** to call up the clipboard.
2. Double-click a block in the clipboard, the current content will be quickly copied, and the current block will be moved to the top of the clipboard.
3. Select the destination to paste.
4. Move the mouse to a certain area of the clipboard, click the upper **X** to delete the current content; click **Clear All** at the top to empty the clipboard.

#### Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


#### Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
