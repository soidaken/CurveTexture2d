# 曲线纹理 2d CurveTexture2d

基于 CocosCreater 实现的 2d 的曲线纹理,可在编辑器中实时编辑.  
The 2d curve texture based on CocosCreater can be edited in real time in the editor

> 此插件扩展目前支持 CocosCreater 3.6.0~3.8.7

![](/imgs/1.gif)

## 如何获取

1. 点击 [Cocos Store](https://store.cocos.com/app/search?name=soida)
2. 下载然后安装插件
3. 插件会自动复制组件源码 `curvetexture` 和样例场景 `curvetexture-sample` 到项目中

## 如何使用

1. 安装好后,需要编辑器如下设置
   - 开启 偏好设置 实验室 `保持场景主循环运行`
   - 开启 项目设置 功能裁剪 `3D基础功能`
2. 新建一个曲线纹理节点 ![](/imgs/2.gif)
3. 新建一个`TANGENT_MODE` 的曲线纹理节点![](/imgs/3.gif)
4. 新增和减少控制点 ![](/imgs/4.gif)
5. 让地表跟随地形,做一个完整的地形![](/imgs/5.gif)
6. 如果需要调整渲染起始位置![](/imgs/6.gif)
7. 如果需要同步生成物理属性![](/imgs/7.gif)
8. 可以根据需要调整渲染的厚度![](/imgs/8.gif)
9. 添加个小球然后运行看下效果![](/imgs/9.gif)
10. 再添加个小车,增加点地形 ![](/imgs/10.gif)
