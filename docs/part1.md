## 书的目录

- 分为25章节和4个附录前3章主要是带读者认识 JavaScript 这门编程语言，包括它的历史渊源、基本用法、基本概念与基本语法

- 第4至第7章深入讲解 JavaScript 的语法以及特性

- 第8章讲 BOM

- 第9章讲客户端检测

- 第10到第12章讲 DOM

- 第13章到第17章讲解常见应用

- 第18章到第21章是 JavaScript 的扩展应用

- 第22章到第24章讲解 JavaScript 高级应用

- 第25章是提到截至本书定稿日期的一些新兴 API

- 附录A：ECMAScript Harmony

- 附录B：严格模式

- 附录C：JavaScript 库

- 附录D：JavaScript 工具
  
  ## 读第一章
  
  ### 目录
  
  总共4小节，前三节为内容介绍，末节为对本章内容的总结。
  
  ### JavaScript 简史
  
  JavaScript 诞生的契机：Web 日益流行，而用户完成一个简单的表单验证需要频繁地与服务器交互数据。有的时候等待了30秒，结果仅仅因为用户输入的格式不对或者必填项没有填写而需要重新填写一遍，用一门客户端脚本语言来解决这些问题就成为时代的命题。
  主导公司：Netscape（网景）公司
  作者：布兰登·艾奇（Brendan Eich）
  年份：1995年2月（诞生 JavaScript 的前身 LiveScript，它也能在服务器端运行，服务器端名为 LiveWrite。后来改名为 JavaScript，因为Java 在当时很流行，而 Netscape 公司与发明 Java 语言的 Sun 公司进行了合作，想借助 Java 的名声将这门新生的客户端脚本语言推广出去)
  ECMAScript 诞生：1997年 ECMAScript 诞生。ECMAScript 是 JavaScript 的标准，是为了解决不同浏览器开发商运行 JavaScript 各自有自己的标准，甚至专门开发另一种客户端脚本语言，这会使得一些网页的开发者很头疼，他们需要解决一大堆浏览器兼容性问题，也不利于整个行业的健康发展。ECMAScript 是由 ECMA（欧洲计算机制造商协会）组织会议审议，根据审议结果制定的通用的 JavaScript 语法、语义标准。

### JavaScript的实现

组成要素：ECMAScript、DOM 与 BOM。
ECMAScript 是核心，决定了 JavaScript 的基本语法与语义。DOM 就是文档对象模型，是 JavaScript 操作 HTML 元素的依据。BOM 是浏览器对象模型，是 JavaScript 获取和改变浏览器内置的一些属性的根本。

- ECMAScript
  
  - 它由 ECMA （前身为**欧洲计算机制造商协会**，European Computer Manufacturers Association）组织制定的第262号标准，即 ECMA-262，这个标准定义了 JavaScript 这门语言的基础。
  - ECMA-262 规定了这门语言的**语法**、**类型**、**语句**、**关键字**、**保留字**、**操作符**和**对象**。
