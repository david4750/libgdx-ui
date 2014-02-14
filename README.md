# 让CocoStudio变成libgdx的UI编辑器


### WIKI : https://github.com/121077313/cocostudio-ui-libgdx/wiki
### 问答 : https://github.com/121077313/cocostudio-ui-libgdx/wiki/疑难解答



更新记录

2014.2.12 
* 更新demo.zip,展示了如何使用CocoStudioUIEditor 创建一个界面,如何获取控件 添加事件.

2014.2.13 
* 整合的Demo项目,内有多种使用场景和案例,后续也会继续更新demo. 
* 处理了UIEditor 的一些BUG.
* 添加了ScrollPane 支持
* 添加问答wiki
* 添加CheckBox支持,CheckBox只有选中和未选中2个图片.
* 修复了锚点问题,现在坐标已经能完全对齐
* 修复渲染层级问题,能正常的根据渲染层级进行zindex排序
* 暂时去掉了Touchable属性,还没能很好解决不同控件覆盖事件传递等问题
* 修改了demo项目,按任意键来切换查看不同场景
* 移植了 UI编辑器示例项目:DemoHead_UI,DemoLogin,DemoMap,DemoShop,SampleChangeEquip. 部分项目还未完全移植成功
* 修复了TextField的MessageText属性 

2014.2.14
* 添加了动画模式的解析,增加了对应demo  SampleUIAnimation,但是还不清楚为什么实际动作比编辑器里面看到的动作慢半拍.
* 重构了代码
* 添加了LoadingBar控件,暂时使用Image代替实现...也就是说LoadingBar就是一个图片.仅此而已.
* CocoStuido的全部Demo移植完毕.一共6个.
