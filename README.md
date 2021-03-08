# generator-yz-vue

基于Yeoman创建的脚手架示例

1. 新建一个以generator开头的文件夹，如mkdir generator-vue-cli
2. 全局安装 **yoman**模块： yarn global add yo
3. 在新建的文件夹中初始化文件目录：yarn init -y
4. 安装 **yeoman-generator**模块：yarn add yeoman-generator
5. 在根目录下新建如下目录：generators/app/templates，其中templates中存放的是希望脚手架安装的文件。
6. 编写入口文件：generators/app/index.js
7. 将此模块链接到全局：yarn link
8. 调用脚手架：新建一个文件夹，在命令中切换到该文件夹，在命令行中输入命令：yo vue-cli