# vue-element
饿了么组件 使用总结
* **1. Table中，通过 Scoped slot 可以自定义列的内容；**
  * 可以获取到 row, column, $index
  scope.$index：在表格循环数据tableData4中的索引。
  scope.row: 获取当前行信息。
  scope.column：
  
* **2. 事件中 传入($event)**
  * 在回调函数中 event.currentTarget的值就是 当前绑定事件的元素。

