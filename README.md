# 我的Sublime Text4配置文件

操作系统：Windows 10系统（不同的操作系统mac/linux，在 sublime配置上会有微小的差别）
### 装的插件：
1. ChineseLocalizations：汉化
2. Emmet：Web前端开发工具，代码自动补齐
3. Package Control：sublime的包管理插件
4. Scss: 前端.scss文件代码高亮
5. SideBarEnhancements：增强侧边栏插件，[可用于浏览器预览](http://www.cnblogs.com/binstyle/p/5304842.html)
6. Vue Syntax Highlight：前端vue框架，语法高亮

### 安装步骤
- 在新系统上安装好 sublime4和git 之后，在git中：
```console
cd ~/AppData/Roaming/'Sublime Text'/
git clone git@github.com:Yliku/sublime-config.git  // 以ssh的方式下载该库，需要先配好SSH
mv sublime-config Packages                         // 将sublime-config重命名为sublime配置的文件夹名
```
- 安装 Package Control，[官网安装指导](https://packagecontrol.io/installation)：
   1. 打开sublime的控制台：ctrl+shift+p（Win/Linux）
   2. 输入：Install Package Control，安装后重启sublime，这样所有的扩展包会自动安装上。
