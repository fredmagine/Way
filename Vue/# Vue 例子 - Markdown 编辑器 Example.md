# Vue 例子 - Markdown 编辑器 Example

## 开始

1. 坑一， 不导入外部模块直接运行

   ```
   import marked from 'marked'
   import _ from 'lodash'
   ```

   ​

2. 坑二， 导入外部模块地点错误

   ```
   应该在 组件.vue 中直接导入
   ```

3. 坑三， @input 绑定**update**方法

   ```
   @input 绑定方法 不可命名为 update // 原因是 update 覆盖
   ```

   ​