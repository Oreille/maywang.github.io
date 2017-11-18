
## **我是谁？**
 
  通过需求将实现生活与自我意识的相互转变。
  
##  **为什么写这些？**

- 1. 防止知识遗忘。
- 2. 快速查找知识。
- 3. 让大家更简单更直接的认识我。 

## **最后我成了这样**

### 进入首页<a href='https://oreille.github.io'>oreille.github.io</a>

### 安装 sublime text 3
安装Markdown 插件：https://github.com/SublimeText-Markdown/MarkdownEditing

### git 客户端
https://desktop.github.com/

- git config --global user.name "王晓霞"
- git config --global user.email "maywang05@126.com"


## **本地启动服务**
### 安装node
- 下载：                         https://nodejs.org/en/download/ 
- 安装淘宝npm：                  sudo npm install -g cnpm --registry=https://registry.npm.taobao.org
- 安装supervisor（类似热加载）：  sudo cnpm -g install supervisor
- 安装express(不是必须):         sudo cnpm install -g express-generator@4
- 构建node-express项目(不是必须)： express node-express
###  进入node-express文件夹 cd node-express
- 安装依赖 cnpm install  
###  启动项目
  进入run文件夹> cd  run
  mac系统输入命令   ./run-node-express.sh
  windows系统命令  run-node-express.bat
  node-express/bin>  supervisor www 或 node www
###  访问项目
 http://localhost:3000

 control + c 停止服务
 
 
### 本地启动
#### 第一步: 点击软件下方的 terminal
#### 第二步：输入 supervisor node-express/bin/www

### 新增本地文件加入版本控制
#### 在对应的文件加或文件上快捷键 option+command+a  (文件由红色变绿色)

### 将本地文件发布到远程服务器
  command + k
### 将远程服务器变更文件更新到本地
  command + T

