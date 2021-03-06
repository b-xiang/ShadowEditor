# 用户界面

Shadow Editor的用户界面包括菜单栏、工具栏、场景编辑区、场景层次图、脚本列表、属性面板、动画编辑区、状态栏、脚本编辑器、场景播放器等几部分。

![image](image/ui.png)

## 菜单栏

由场景、编辑、几何体、光源、资源、地形、组件、启动、选项、帮助几个菜单组成。

菜单栏最右侧是three.js的版本。

![image](image/menuBar.png)

## 工具栏

由选择、平移、旋转、缩放、添加模型等几个工具组成。

![image](image/toolbar.png)

## 场景编辑区

可以使用鼠标编辑场景中的物体，进行平移、旋转、缩放等操作。

选中物体，按`Del`键可以删除物体。

![image](image/sceneEditor.png)

## 场景层次图

提供场景中所有物体的树状视图。

选中树节点，按`Del`键可以删除物体；双击树节点，可以使场景编辑器视角切换到该物体；拖动树节点到另一个节点上，可以让该物体变为另一个物体的子元素。

![image](image/hierachy.png)

## 脚本列表

单击新建脚本，可以添加`Javascript`脚本，支持语法高亮和智能提示。关闭脚本窗口会自动保存。

![image](image/scriptPanel.png)

## 属性面板

为不同物体提供可视化编辑属性功能。到目前版本，已经具有33种不同组件面板。

![image](image/propertyPanel.png)

## 动画编辑区

具有时间轴，可以进行补间动画编辑，可以创建分组。还提供资源管理、日志等功能。

![image](image/animationPanel.png)

## 状态栏

提供场景中所有物体的物体数、顶点数、三角形数。

![image](image/statusBar.png)

## 脚本编辑器

新建和编辑Javascript、GLSL、ProgramInfo时，会出现脚本编辑器，带语法高亮和智能提示，非常方便。

![image](image/scriptEditor.png)

## 场景播放器

启动场景后，会打开场景播放器界面。播放背景音乐，执行所有脚本和动画。

![image](image/player.png)
