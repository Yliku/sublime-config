# sublime-config
我的Sublime Text3配置文件

我使用的操作系统是Windows 7系统，不同的操作系统mac/linux，在 sublime配置上会有微小的差别。

我自己装的插件有：
1. SideBarEnhancements：增强侧边栏插件，[可用于浏览器预览](http://www.cnblogs.com/binstyle/p/5304842.html)
2. ConvertToUTF8 或者 GBK Encoding Support：	支持多种编码，解决打开文件中的中文乱码问题
3. Emmet：Web前端开发工具，代码自动补齐
4. Vue Syntax Highlight：前端vue框架，语法高亮
5. view in browser：在默认的浏览器中预览HTML代码

### 安装步骤
- 在新系统上 sublime 3/2 和 git安装好之后，在git中：
```console
cd ~/AppData/Roaming/Sublime Text 3/Packages/	进入sublime配置文件User所在的目录
git clone https://github.com/Yliku/sublime-config.git 	以http的方式下载该库
mv sublime-config User          将sublime-config重命名为sublime配置的文件夹名
```

- 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的扩展包会自动安装上。
- ctrl 跟 导引号/反引号（Tab上面的键）来呼叫出 command console 
