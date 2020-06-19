"# frontend-learning" 

## 子绝父相的由来
子级是绝对定位的话，父级要用相对定位。
* 子级绝对定位，不会占有位置，可以放到父盒子里任何一个地方，不会影响其它兄弟盒子。
* 父盒子需要加定位限制子盒子在父盒子内显示
* 父盒子布局时，需要占有位置，因此父亲只能是相对定位。

这就是子绝父相的由来，所以相对定位经常用来作为绝对定位的父级。
总结：因为父级需要占有位置，因此是相对定位，子盒子不需要占有位置，则是绝对定位。
当然，子绝父相不是永远不变的，如果父元素不需要占有位置，子绝父相也会遇到。