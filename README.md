# 曲线纹理 2d CurveTexture2d

基于 CocosCreater 实现的 2d 的曲线纹理,可在编辑器中实时编辑.  
The 2d curve texture based on CocosCreater can be edited in real time in the editor

## 如何获取 How to get it

1. 在 [Cocos Store](https://store.cocos.com) 中搜索 soida/曲线纹理/CurveTexture/curve 等关键字即可看到.
2. 下载或者安装后(或许需要重启编辑器),在某个节点的`属性检查器`中点击最下方的`添加组件/add a component`,搜索`CurveTexture2d/曲线纹理2d`即可添加成功. 见下图:

   ![](./imgs/help1.jpg)

## 如何使用 how to use it

1. 如果你已经成功添加组件,恭喜你,成功了一半.
2. 你会看到伴随`CurveTexture`组件同时自动添加了一个`cc.MeshRenderer`组件,不用设置它,让它在那里就行.
3. 现在,画面中还没有任何改变.按照下面操作添加对应贴图:

![](./imgs/help2.gif)

4. 现在你可以在`场景编辑器`中看到如下画面

![](./imgs/help2.jpg)

## 常用的编辑操作 Available edit operations

1. 调整一个或者多个控制点 Adjust one or more control points
   ![](./imgs/help3.gif)

2. 新增一个或者多个控制点`(Ctrl+D)` add one control point
   ![](./imgs/help4.gif)

3.
