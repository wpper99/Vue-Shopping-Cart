# Vue-Shopping-Cart
## Vue实现购物车小案例<br>
## 一、购物车需求
1. 渲染功能

2. 删除功能
 
3. 修改个数

4. 全选反选

5. 统计 选中的 总价 和 总数量 

## 二、实现思路
1.基本渲染：  v-for遍历、:class动态绑定样式

2.删除功能 ： v-on 绑定事件，获取当前行的id

3.修改个数 ： v-on绑定事件，获取当前行的id，进行筛选出对应的项然后增加或减少

4.全选反选 

1. 必须所有的小选框都选中，全选按钮才选中 → every
2. 如果全选按钮选中，则所有小选框都选中
3. 如果全选取消，则所有小选框都取消选中

声明计算属性，判断数组中的每一个checked属性的值，看是否需要全部选

5.统计 选中的 总价 和 总数量 ：通过计算属性来计算**选中的**总价和总数量

## 三、实现购物车效果

![Image text](https://github.com/wpper99/Vue-Shopping-Cart/blob/master/Shopping-Cart/img/%E8%B4%AD%E7%89%A9%E8%BD%A6.png)

