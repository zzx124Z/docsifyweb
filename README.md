# ○ 手撕猪的附件表

这是全新的导航网站，里面将记录每期视频中需要用到的软件和网页。

**你可以在浏览器中使用Ctrl+F通过视频编号快速查询。**

[B站主页](https://space.bilibili.com/1776215751?spm_id_from=333.1007.0.0)

> [!CAUTION]
>
> 本网站资源仅供分享，如遇网页问题请及时联系。

------

#### 001.[我的世界网页版]甚至能开光影玩服务器？！

1. mc.js.cool：https://www.mc.js.cool/

2. IMC(直玩)：https://ws.imc.re/eaglerx/

   IMC(官网)：https://ws.imc.re/

3. classic.minecraft.net：https://classic.minecraft.net/?join=

   

------

#### 002.[我的世界JAVA版]从入门到精通

##### 启动器下载：

1.HMCL：https://hmcl.huangyuhui.net/

2.FCL下载站：https://foldcraftlauncher.cn/

3.FCL（github）：https://github.com/FCL-Team/FoldCraftLauncher

##### 资源站：

1.Modrinth：https://modrinth.com/

2.MC百科：https://www.mcmod.cn/

3.CurseForge：https://www.curseforge.com/minecraft

##### 其他：

1.MC百科：https://www.mcmod.cn/

2.中文 Minecraft Wiki：https://zh.minecraft.wiki/

------

#### 003.  0成本！自制一个属于你的网站！

##### 准备工作：

1.Node.js ：https://nodejs.org/zh-cn

2.docsify官网：https://docsify.js.org/#/

3.Typora 官方中文站：https://typoraio.cn/

4.Git官网：https://git-scm.com/

5.hugo官网：https://gohugo.io/

6.hugo主题：https://themes.gohugo.io/

7.GitHub官网：https://github.com/

8.Watt Toolkit官网：https://steampp.net/

##### docsify建站流程（代码部分）：

> [!IMPORTANT]
>
> 一切以视频步骤为准，下方只展示所需代码！

###### ——docsify的安装

1.检查node安装情况

```
node -v
```

2.检查npm安装情况

```
npm -v
```

3.安装docsify工具

```
npm i docsify-cli -g
```

4.初始化docsify文档

```
docsify init ./docs
```

5.本地预览您的网站

```
docsify serve docs
```

##### hugo建站流程（代码部分）：

###### ——hugo的安装

1.检查hugo安装情况

```
hugo version
```

2.创建项目结构

注：quicklystart可自行更改名字

```
hugo new site quickstart
```

3.更改项目根目录（可以理解为在该目录下执行命令）

注：名字前后一致！

```
cd quickstart
```

4.初始化git库

```
git init
```

--5.主题更换后或前启动hugo服务

```
hugo server
```

注：Ctrl+C停止本地预览



###### ——添加文章

1.添加文章

注：my-first-post.md名字自定，注意后缀不要拉掉

```
hugo new content content/posts/my-first-post.md
```

2.添加文章（(stack主题)

```
hugo new content content/post/my-first-post/index.md
```

3.添加文章后预览

```
hugo server -D
```



###### ——手动部署

1.在github上添加新项目和更改“hugo.yaml”文件后远程部署github

注：先使用“…or create a new repository on the command line“前三行指令

```
echo "# demohugo" >> README.md
git init
git add README.md
```

2.将文件移至缓冲层

```
git add .
```

3.配置个人信息

注：视频中没有这一步，如果出现与视频中不同的结果或报错，必须输入一下命令。

```
git config --global user.email "your-real-email@example.com"
git config --global user.name "Your Name"
```

4.将剩余指令填入

注：代码仅做示例，以自己的为准！

```
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/example/demohugo.git
git push -u origin main
```

> [!IMPORTANT]
>
> 如果在建站过程中出现问题请仔细看视频操作，如有错误或无法解决的问题请在评论区指出。如遇到错误可以自行翻译一下错误提示，网络问题请稍后重试！

------

#### 004.[我的世界网页版]我在浏览器玩多人服务器！

1.IMC(直玩)：https://ws.imc.re/eaglerx/

2.IMC(官网)：https://ws.imc.re/

------

#### 005.一键拥有个人网站！不用敲命令甚至完全免费！

1.Node.js ：https://nodejs.org/zh-cn

2.docsify官网：https://docsify.js.org/#/

3.Typora 官方中文站：https://typoraio.cn/

4.Git官网：https://git-scm.com/

5.hugo官网：https://gohugo.io/

6.hugo主题：https://themes.gohugo.io/

7.GitHub官网：https://github.com/

8.Watt Toolkit官网：https://steampp.net/

##### 网盘地址：

1.所需工具安装包https://wwey.lanzouu.com/b0138zhvob

,密码:2tk5

2.一键搭建网页程序https://wwey.lanzouu.com/b01391a0ef

,密码:ai1j

> [!IMPORTANT]
>
> 🔹 **免责声明**：  
> - 本工具为**个人开发**，与以下官方项目无任何关联：  
>   - [docsify](https://docsify.js.org/)（Markdown 驱动文档生成器）  
>   - [Hugo](https://gohugo.io/)（Go 语言静态网站生成器）  
> - 功能：简化 **docsify** 和 **Hugo** 的本地部署及 GitHub Pages 发布流程。  
>

------



