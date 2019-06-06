# JavaScript简介

- 诞生于1995年，它的出现主要是用于处理网页中的前端验证

  - 浏览器检查用户输入
  - 动态效果
  - 例如：用户注册界面的用户名规则和密码规则

- NetScape开发了JS的前身，发布了`LiveScript`

- `Sun`将`LiveScript`修改为`JavaScript`

- 标准：`ECMAScript`是一个文档，而这个标准需要各个浏览器厂商来实现

  - 谷歌浏览器的`JavaScript`实现方式为`v8`,此实现方式运行最快

- Java的Script语言

- 网络的脚本语言

- 一个完整的`JavaScript`包括三个部分:

  - `ECMAScript`
  - `DOM`
  - `BOM`

- js语言特点：

  - 解释型语言：不编译，直接运行
  - 类C
  - 动态语言
  - 基于原型的面向对象

- 简单实例：

  - `alert()`弹出对话框
  - `Document.write()`网页主体输出
  - `console.log()` 控制台输出

- 程序例子：

  ```html
  /*主程序*/
  <html>
  	<body>
  	<!--
  		使用JS外部文件
  		使用外部文件推荐使用
  		script引用了外部文件，则不需在内部写script，写了也不会执行
  	-->
  	<script src = "test1.js">
  	</script>
  	<!--
  		使用JS内部文件
  	-->
  	<script>
  	alert("我是内部JS语法：Hello JavaScript!!");
  	</script>
  	
  	<!--
  		在网页主体显示一个button，名称为Please Click button触发事件为弹出一个对话框
  		单双引号的问题：外部用双引号，内部用单引号，避免错误
  	-->
  	<button onclick = "alert('Hello JavaScript!!你点我干什么？？');">Please Click
  	
  	</button>
  	
  	<!--
  		单引号位置和双引号位置可以互换
  		这个是建立一个超链接
  		这个格式不大一样
  	-->
  	
  	<a href = 'javascript:alert("Hello JavaScript!!你又点我");'>Please Click Also</a>
  	<!------------------------这种格式不推荐------------------------------------------>
  	</body>
  </html>
  
  <!--
  	JS的位置：
  		1. 可以直接在标签中写入
  		2. 直接在本文件中写script
  		3. 可以再外部文件中写，在文件中调用
  -->
  ```

  ```javascript
  alert("我是外部JS语法：Hello JavaScript!!");
  /*文件地址：test1.js*/
  ```

  

