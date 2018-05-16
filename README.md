
## 街机游戏项目

### 如何运行本应用
本项目未使用构建工具，将这个库下载到本地然后用浏览器打开index.html即可运行，或者，你也可以访问本项目的 [GitHub Pages](https://guanzhengwei.github.io/p1/) 来运行。

### 项目概述
你将获得可视化资源和游戏循环引擎；使用这些工具时，你必须向游戏添加一系列实体（包括玩家角色和敌人），以重新创建经典街机游戏“青蛙过河”。

### 项目详情

只需完成app.js文件中的 Enemy、Player类的创建即可完成此项目，项目中的其它所需代码文件已创建完毕。

#### 创建Enemy类

Enemy属性：
* 坐标x
* 坐标y
* 速度s
* 敌人图片sprite

Enemy方法：
* 更新敌人坐标update函数 
* 在屏幕上画出敌人render函数 

#### 创建Player类

Player属性：
* 坐标x
* 坐标y
* 敌人图片sprite

Player方法：
* 更新玩家坐标updae函数 
* 在屏幕上画出玩家render函数 
* 处理玩家输入函数handleInput函数 
* 检查碰撞函数checkCollisions函数 
