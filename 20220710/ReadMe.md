# 教程地址：
[MDN web docs](https://developer.mozilla.org/zh-CN/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents "3")

自个打分：50 ，完成一半。

# 主动学习：一个动态的购物单
#### 作为文章的收尾，我们想给你一个小小的挑战 — 我们要做一个简单的购物单的例子，使用表单的输入框和按钮动态的向购物单中添加购物项。在输入中添加项，然后按下按钮：

- 购物项应该出现在清单中。
- 每个购物项都应该给出一个按钮，可以按下按钮从清单中删除该项。
- 输入框应该是空白的并已聚焦，为你准备好输入另一个项。
- 完成后的演示程序看起来有点像这样的：

[![示例](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents/shopping-list.png "示例")](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents/shopping-list.png "示例")

#### 要完成实验，要按照下面的步骤，确保购物单的行为如上所述。

1.首先 ，下载shopping-list.html文件，并存入本地。你会看到它有一些极小的 CSS，一个带有 label、input 和 button 的 list 和一个空的 list 以及`<script>` 元素。要添加的所有程序都在 script 里面。
2. 创建三个变量来保存 list(`<ul>`)、`<input>`和`<button>`元素的引用。
3. 创建一个函数响应点击按钮。
4. 在函数体内，开始要在一个变量中存储输入框的当前值。
5. 然后，为输入框元素设置空字符 - ''使其为空
6. 创建三个新元素 — 一个 list 项（`<li>`），`<span>`和 `<button>`，并把它们存入变量之中。
7. 把 span 和 button 作为 list 项的子节点。
8. 把之前保存的输入框元素的值设置为 span 的文本内容，按钮的文本内容设置为'Delete'
9. 把 list 项设置为 list 的子节点。
10. 为删除按钮绑定事件处理程序。当点击按钮时，删除它所在的整个 list 项。
11. 最后，使用focus()方法聚焦输入框准备输入下一个购物项。

##### [跳转github](https://github.com/mdn/learning-area/blob/master/javascript/apis/document-manipulation/shopping-list-finished.html "跳转")