# 两列布局
两列自适应布局是指一列由内容撑开，另一列撑满剩余宽度的布局方式
## float+overflow:hidden
普通的两列布局：浮动+margin
自适应两列布局：float+overflow:hidden
这种方法主要通过overflow触发BFC，而BFC不会可以清除浮动，由于设置overflow:hidden不会触发IE6的haslayout属性，所以需要设置zoom:1来兼容IE6