##渐变色

渐变色可以用来填充举行,圆角矩形,椭圆,贝塞尔曲线,星形和多边形.PaintCode支持多步渐变色.你也可以选择(由角度定义的或者由两个点定义的)线性渐变色或者圆形渐变色.渐变色依赖于他们使用的颜色,当这些颜色调整了,渐变色也会根据颜色自动更新.

##使用渐变色
想要使用渐变色, 只需要点击拖动渐变色连接点到画布上面的形状:

![assign_gradient_connection](assets/gradients/assign_gradient_connection.png)

你也可以简单的在内省器里面点击空的stroke或者fill并从菜单中选择渐变色:

![assign_color_well](assets/gradients/assign_gradient_well.png)

你也可以从弹出按钮菜单中选择渐变色:

![assign_gradient_popup](assets/gradients/assign_gradient_popup.png)

![assign_gradient_popup_context](assets/gradients/assign_gradient_popup_context.png)

这个菜单的项为库中的颜色和渐变色.

##添加新渐变色
有两种方法添加新的渐变色:

- 在库中渐变色列表的顶部点击`+`按钮.
- 在填充弹出菜单中选择`Add new graident...`. 这个操作也会设置新创建的渐变色为当前属性的值.(注意你也可以通过从其他文档拷贝和粘贴来添加渐变色)

##编辑渐变色
你可以通过双击库中的渐变色来编辑它.

![gradientcontrol](assets/gradients/gradientcontrol.png)

你也可以点击内省器中的渐变色槽来显示一个编辑颜色弹框.

![well_editor](assets/gradients/well_editor.png)

这个输入框包含了渐变色的名字. PaintCode为你生成所有的名字, 但是你可以改成更具有描述性的名字.

这个弹框包含了一个特殊的渐变色控制器. 你可以使用它来指定渐变色中每个颜色的位置.

##改变渐变色的色值
要在渐变色中改变颜色,点击在渐变色控制器下面的颜色球.然后从渐变色控制器下面的颜色弹出按钮中选择你想要的颜色.

##在渐变色弹框中方便地调整色值
有时,你需要调整渐变色中颜色的明暗.你可以关掉渐变色弹框,打开颜色弹框,调整颜色,不过这样太不方便了. 
其实, 你可以通过渐变色弹框中右下角的槽来调整.

![gradient_color_adjust](assets/gradients/gradient_color_adjust.png)

