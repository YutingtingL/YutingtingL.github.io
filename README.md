#菜篮子项目首页

#居中
- 盒子居中
``` html
<!-- 必须是块 -->
width:500px;
magin-left:auto;
magin-right:auto;
```

``` html
width:500px;
position:absolute;
left:50%;
magin-left:-250px;
```

- 盒子内容居中
``` html
- text-align:center;
```

##快捷键

- Ctrl+O 打开文件

- Ctrl+Shift+O 打开文件夹

- Ctrl+Shift+T 复制当前行到下一行

- Ctrl+Shift+K 删除当前行

- Ctrl+|  关闭资源管理器

- Ctrl+上下键 调换上下行

- Ctrl+D 选择同类

- ! 快速生成html5

- F1 Enter 格式化


## nodejs

- node  运行环境
- npm   包管理器  国外
- cnpm  淘宝镜像

安装
- npm install -g cnpm --registry=https://registry.npm.taobao.org

- cnpm install

- nmp install gulp -g

### gulp

- 合并 压缩 自动刷新 服务器

- win macos linux

# 知识

- html

- css

- 页面布局 移动端页面开发

## tool

- git  github
- markdown
- gulp

- 自动化构建工具：把生产环境转化为上线环境的代码
- 压缩 文件重命名 目录更改 css转化 错误判断


## all

#### markdown

`#`  `######` h1-h6

`-`  ul
`1.` ol

`[关键字](跳转链接)`  a
`![图片关键字](图片的链接)` img 

`  ```  ```  `   code标签 放代码

#### git  版本管理工具

- git clone url-address  克隆仓库到本地

- git add 

- git commit -m  “提交 注释”

- git pull 和远程仓库同步 （拉取）

- git push 把本地代码提交到远程 （推送）

- git log  显示提交记录

###  node gulp

$ node -v 查看版本号
$ npm -v 

$ cnpm install 包名 -g   全局安装
$ cnpm install 包名 --globe   全局安装

$ cnpm install 包名 --save-dev   安装到当前文件夹 写入
package.json

#### linux

- cd 切换目录
- ls 把目录下的文件列出来