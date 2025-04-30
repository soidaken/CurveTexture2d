# 曲线纹理 2d CurveTexture2d

基于 CocosCreater 实现的 2d 的曲线纹理,可在编辑器中实时编辑.  
The 2d curve texture based on CocosCreater can be edited in real time in the editor

## 如何获取 How to get it

1. 在 [Cocos Store](store.cocos.com) 中搜索 曲线纹理/soida/CurveTexture 关键字即可看到.
2. 下载或者安装后(或许需要重启编辑器),在某个节点的`属性检查器`中点击最下方的`添加组件/add a component`,搜索`CurveTexture2d/曲线纹理2d`即可添加成功. 见下图:

   ![](./imgs/help1.jpg)

## 如何使用 how to use it

1. 如果你已经成功添加组件,恭喜你,成功了一半.
2. 你会看到伴随`CurveTexture`组件同时自动添加了一个`cc.MeshRenderer`组件,不用设置它,让它在那里就行.
3. 在编辑器的`控制台(Console)`中会出现下面提示,你按照提示操作即可
   > [Scene] 还未指定 [ 地形贴图纹理 ],拖入插件默认的 [ terrain-ground ] 贴图即可! (The [Terrain Texture] has not been specified yet, drag in the default [terrain-ground] texture of the plugin!)
4. 接着,会有下面提示,你按照提示操作即可.
   > [Scene] 还未指定[ 地形控制点贴图纹理 ]! 拖入 [ gizmotag ] 资源即可 ([Terrain Control Point Texture] has not been specified yet! Drag in the [gizmotag] resource)
5. 现在你可以在`场景编辑器`中看到如下画面
   ![](./imgs/help2.jpg)
