# 三列布局
## 圣杯布局/双飞翼布局
圣杯布局和双飞翼布局都是由左中右组成，特点为左右两列宽度固定、中间一列宽度自适应和三列高度固定且相等。
圣杯布局和双飞翼布局在大体相同下也存在一点不同，区别在于双飞翼布局中间列需插入一个子节点
* 相同点
  中间列放首位且声明其宽高占满父节点
  被挤出的左右列使用float和margin负值将其拉回与中间列处在同一水平线上
* 不同
  圣杯布局：父节点声明padding为左右列留出空位，将左右列固定在空位上
  双飞翼布局：中间列插入子节点并声明margin为左右列让出空位，将左右列固定在空位上