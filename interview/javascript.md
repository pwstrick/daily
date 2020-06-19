1. [JavaScript的变量名在定义时需要遵守哪些规则？](https://github.com/pwstrick/daily/issues/246)
2. [不能被encodeURIComponent()函数编码的字符有哪些？](https://github.com/pwstrick/daily/issues/247)
3. [如何获得Select元素（选择框）中选中项的索引？](https://github.com/pwstrick/daily/issues/248)
4. [JavaScript的内置对象有哪些。](https://github.com/pwstrick/daily/issues/249)
5. [如何为一个\<p>元素添加CSS类primary？](https://github.com/pwstrick/daily/issues/250)
6. [与鼠标相关的事件有哪些？](https://github.com/pwstrick/daily/issues/251)
7. [如何通过jQuery的方式获得代码中单选框的选中值。](https://github.com/pwstrick/daily/issues/252)
8. [执行下面的代码，在控制台输出的x为__________，y为__________。](https://github.com/pwstrick/daily/issues/253)
```javascript
var x = 0, y = 0;
x
++
y
console.log(x, y);
```
9. [调用下面代码中的函数，最终返回的结果为__________。](https://github.com/pwstrick/daily/issues/254)
```javascript
function isArray() {
  return
  true;
}
isArray();
```
10. [执行下面的代码后，在控制台输出的y为__________。](https://github.com/pwstrick/daily/issues/255)
```javascript
var y,
  x = 1;
y = x+++x;
```
11. [2+true等于__________，'6'+9等于__________。](https://github.com/pwstrick/daily/issues/256)
12. [4+3+2+"1"等于__________，"1"+2+4等于__________。](https://github.com/pwstrick/daily/issues/257)
13. [(1, 5 - 1) * 2 等于__________。](https://github.com/pwstrick/daily/issues/258)
14. [执行下面的代码后，在控制台输出的y为__________。](https://github.com/pwstrick/daily/issues/259)
```javascript
var x = "1", y;
switch (x) {
  case 1:
    y = 1;
    break;
  case 2:
    y = 2;
    break;
  default:
    y = 0;
}
console.log(y);
```
15. [!function(){}的返回值是__________。](https://github.com/pwstrick/daily/issues/260)
16. [7 - "a"等于__________，7 / 0等于__________。](https://github.com/pwstrick/daily/issues/261)
17. [3..toFixed(2)得到的结果为__________。](https://github.com/pwstrick/daily/issues/262)
18. [parseFloat('12.3.4')返回的结果为__________。](https://github.com/pwstrick/daily/issues/263)
19. [Number(012)返回的结果为__________，Number("0xA")返回的结果为__________。](https://github.com/pwstrick/daily/issues/264)
20. [在下面的代码中，Number()函数的参数是一个对象，最终的结果为__________。](https://github.com/pwstrick/daily/issues/265)
```javascript
var numberObj = {
  valueOf: function() {
    return {};
  },
  toString: function() {
    return "10";
  }
};
Number(numberObj);
```
21. [~{}等于__________，~1.25等于__________。](https://github.com/pwstrick/daily/issues/266)
22. [以下代码最终在控制台输出的结果为__________。](https://github.com/pwstrick/daily/issues/267)
```javascript
var a = {},
  b = { name: "ping" },
  c = { name: "wen" };
a[b] = 10;
a[c] = 20;
console.log(a[b]);
```
23. [[] == ![]得到的结果为__________。](https://github.com/pwstrick/daily/issues/268)
24. [[] + {}得到的结果为__________，{} + []得到的结果为__________。](https://github.com/pwstrick/daily/issues/269)
25. [Array.prototype.isPrototypeOf([1, 2])的结果为__________。](https://github.com/pwstrick/daily/issues/270)
26. [下面代码最终的打印结果是__________。](https://github.com/pwstrick/daily/issues/271)
```javascript
var obj1 = {
  names: []
};
var obj2 = obj1.names;
obj2.push("strick");
console.log(obj1.names);
```
27. [在下面的代码中，调用了三次test()方法，得到的结果分别是__________、__________ 和__________。](https://github.com/pwstrick/daily/issues/272)
```javascript
var str = "pw1",
  pattern1 = /\d/,
  pattern2 = /\d/g;
pattern1.test(str);
pattern2.test(str);
pattern2.test(str);
```
28. [执行下面的代码后，arr1.length为__________。](https://github.com/pwstrick/daily/issues/273)
```javascript
var arr1 = "ping".split(""),
  arr2 = arr1.reverse(),
  arr3 = "pw".split("");
arr2.push(arr3);
```
29. [执行下面的代码后，arr数组的值为__________。](https://github.com/pwstrick/daily/issues/274)
```javascript
var arr = [4, 1, 5, 2, 3];
arr.sort(function(a, b) {
  return a > b;
});
```
30. [[1, 2, 3, 4, 5].splice(-2)的值为__________。](https://github.com/pwstrick/daily/issues/275)
31. [[1, 2, 3, 4, 5].slice(NaN, 1)的值为__________。](https://github.com/pwstrick/daily/issues/276)
32. [下面代码执行后，在控制台会输出b变量，得到的结果是__________。](https://github.com/pwstrick/daily/issues/277)
```javascript
(function() {
  var a = b = 5;
})();
console.log(b);
```
33. [1 instanceof Number的返回值是__________，2 in [1,2]的返回值是__________。](https://github.com/pwstrick/daily/issues/278)
34. [typeof undefined的返回值是__________，typeof null的返回值是__________。](https://github.com/pwstrick/daily/issues/279)
35. [将Object的toString()方法分别应用于null和undefined（如下所示），得到的结果为__________和__________。](https://github.com/pwstrick/daily/issues/280)
```javascript
var toString = Object.prototype.toString;
toString.call(null);
toString.call(undefined);
```
36. [执行下面的代码，结果的输出顺序是__________、__________、 __________。](https://github.com/pwstrick/daily/issues/281)
```javascript
console.log(1);
setTimeout(function() {
  console.log(2);
}, 0);
console.log(3);
```
37. [请简单描述一下你对JavaScript的理解。](https://github.com/pwstrick/daily/issues/4)
38. [JavaScript有哪些优势和劣势？](https://github.com/pwstrick/daily/issues/282)
39. [相等（==）和全等（===）运算符有哪些区别？](https://github.com/pwstrick/daily/issues/283)
40. [在JavaScript中，字面量是指什么？](https://github.com/pwstrick/daily/issues/284)
41. [分号会在什么时候自动补全？自动补全有什么弊端？](https://github.com/pwstrick/daily/issues/285)
42. [什么是严格模式？严格模式有哪些限制？](https://github.com/pwstrick/daily/issues/286)
43. [undefined和null的有哪些异同？](https://github.com/pwstrick/daily/issues/287)
44. [请说明JavaScript中的原生对象（native objects）和宿主对象（host objects）。](https://github.com/pwstrick/daily/issues/288)
45. [全局函数eval()有什么作用？](https://github.com/pwstrick/daily/issues/289)
46. [请简单描述一下你所理解的原型链。](https://github.com/pwstrick/daily/issues/290)
47. [用new运算符创建对象时，例如new Fn()，具体的创建过程有哪几步？](https://github.com/pwstrick/daily/issues/291)
48. [JSON格式的数据与XML格式的数据相比，有哪些优势？](https://github.com/pwstrick/daily/issues/292)
49. [函数声明和函数表达式有哪些区别？](https://github.com/pwstrick/daily/issues/293)
50. [Function构造器有哪些功能？](https://github.com/pwstrick/daily/issues/294)
51. [执行下面的代码，为何输出的都是3？](https://github.com/pwstrick/daily/issues/295)
```javascript
for (var i = 0; i < 3; i++) {
  setTimeout(function() {
    console.log(i);
  }, 0);
}
```
52. [请谈谈你对闭包的理解。](https://github.com/pwstrick/daily/issues/296)
53. [什么是事件循环？](https://github.com/pwstrick/daily/issues/297)
54. [如果一个全局变量没有事先声明，那么在控制台能否输出它的值？](https://github.com/pwstrick/daily/issues/298)
55. [如何用脚本获取当前显示器的分辨率？](https://github.com/pwstrick/daily/issues/299)
56. [document.write()和innerHTML有哪些区别？](https://github.com/pwstrick/daily/issues/300)
57. [请介绍一下DocumentFragment类型的节点。](https://github.com/pwstrick/daily/issues/301)
58. [HTML元素的特性和属性是怎么定义的？](https://github.com/pwstrick/daily/issues/302)
59. [jQuery有哪些特色？](https://github.com/pwstrick/daily/issues/303)
60. [在jQuery中有哪些方法可以删除元素。](https://github.com/pwstrick/daily/issues/304)
61. [jQuery UI是什么？](https://github.com/pwstrick/daily/issues/305)
62. [请用JavaScript实现冒泡排序。](https://github.com/pwstrick/daily/issues/306)
63. [请实现一个遍历至100的循环，在能被3整除时输出“three”，在能被5整除时输出 “five”，在能同时被3和5整除时输出“all”。](https://github.com/pwstrick/daily/issues/307)
64. [封装一个isInteger()函数，用于检测传入的值是整数。](https://github.com/pwstrick/daily/issues/308)
65. [请重新封装一个isNaN2()函数，此函数弥补了全局函数isNaN()的不足。](https://github.com/pwstrick/daily/issues/309)
66. [编写一个函数，能让两个并不大的小数正确相乘。](https://github.com/pwstrick/daily/issues/310)
67. [统计字符串“xxxxyyydda”中每个字母出现的次数。](https://github.com/pwstrick/daily/issues/311)
68. [执行a == 1 && a == 2 && a == 3，返回的结果是true，那么a的值是什么？](https://github.com/pwstrick/daily/issues/312)
69. [如何判断对象中的某个属性是继承而来的？](https://github.com/pwstrick/daily/issues/313)
70. [如何用JavaScript实现对象继承？](https://github.com/pwstrick/daily/issues/314)
71. [怎么实现深拷贝？](https://github.com/pwstrick/daily/issues/315)
72. [在网页中实现一个倒计时，能够动态显示“××天××时××分××秒” 。](https://github.com/pwstrick/daily/issues/316)
73. [请用多种方式获取当前时间的毫秒数。](https://github.com/pwstrick/daily/issues/317)
74. [如何判断某一年是闰年？](https://github.com/pwstrick/daily/issues/318)
75. [如何计算两个日期相隔的天数？](https://github.com/pwstrick/daily/issues/319)
76. [请编写一个格式化字符串的函数，例如传入“我的名字叫{0}”和“strick”，返回“我的名字叫strick”。](https://github.com/pwstrick/daily/issues/320)
77. [用JavaScript封装一个函数，可实现整数的千分位逗号分隔符（不用考虑小数），例如12345用12,345表示。](https://github.com/pwstrick/daily/issues/321)
78. [编写一个函数，用于清除字符串前后的空格。](https://github.com/pwstrick/daily/issues/322)
79. [如何将字符串“get-element-by-id”转化成驼峰表示法的“getElementById”？](https://github.com/pwstrick/daily/issues/323)
80. [用数组方法把数组中的元素（假设元素值都是数字）加起来，得到的和赋给result变量。](https://github.com/pwstrick/daily/issues/324)
81. [不用循环语句（for、while等）创建一个长度为50的数组，每个元素的值等于它的索引。](https://github.com/pwstrick/daily/issues/325)
82. [设计一个函数能够补全整数的前置零，例如为3补全两个前置零，得到的结果为“003”。](https://github.com/pwstrick/daily/issues/326)
83. [有一个数组，其值为[1,[2,[3,4,2],2],5,[6]]，如何才能输出[1,2,3,4,2,2,5,6]？](https://github.com/pwstrick/daily/issues/327)
84. [请封装一个函数，用于判断某个数是否是质数。](https://github.com/pwstrick/daily/issues/328)
85. [请封装一个函数，可序列化URL中的查询字符串，也就是把字符串转换为一个包含所有参数的对象。](https://github.com/pwstrick/daily/issues/329)
86. [设计一个函数，用于判断一个HTML元素是另一个HTML元素的后代。](https://github.com/pwstrick/daily/issues/330)
87. [创建一个\<dd>元素，设置该元素的内容为4，并插入到id属性为“third”的\<dd>元素之前。要求用DOM方法实现。](https://github.com/pwstrick/daily/issues/331)
88. [如何动态的添加外部脚本？](https://github.com/pwstrick/daily/issues/332)
89. [用多种方式为一个<div>元素设置一个名为ui-border的CSS类。](https://github.com/pwstrick/daily/issues/333)
90. [请封装一个函数，模拟getBoundingClientRect()方法，但只要返回元素到视口顶部（top）和左边（left）的距离。](https://github.com/pwstrick/daily/issues/334)
91. [如何禁用HTML文档中的提交按钮？](https://github.com/pwstrick/daily/issues/335)
92. [用JavaScript为HTML元素设置两个CSS属性：字体大小和宽度，把字体大小设为18px，宽度设为100px，请用多种方式实现。](https://github.com/pwstrick/daily/issues/336)
93. [有一个div元素，其宽度设为了百分数，如何用JavaScript获得经过计算后的真正宽度？](https://github.com/pwstrick/daily/issues/337)
94. [如何用JavaScript隐藏一个按钮？](https://github.com/pwstrick/daily/issues/338)
95. [假设有一个按钮，如何在点击类型的事件处理程序中阻止事件传播。](https://github.com/pwstrick/daily/issues/339)
96. [请封装一个注册事件的函数，要求能够跨浏览器运行。](https://github.com/pwstrick/daily/issues/340)
97. [什么是事件委托？请用一个例子来描述委托？](https://github.com/pwstrick/daily/issues/341)
98. [不使用第三方类库，用DOM方法读取复选框中选中的值。](https://github.com/pwstrick/daily/issues/342)
99. [用多种方式移除选择框（Select元素）中的选项（Option元素）。](https://github.com/pwstrick/daily/issues/343)
100. [如何用<iframe>元素实现无刷新文件上传。](https://github.com/pwstrick/daily/issues/344)
101. [HTML5新增了FileReader对象，如何利用这个对象来读取上传按钮中选择的文件？](https://github.com/pwstrick/daily/issues/345)
102. [不借助第三方类库，请实现一次简单的Ajax请求。](https://github.com/pwstrick/daily/issues/346)
103. [请解释JSONP的工作原理，并用代码描述其过程。](https://github.com/pwstrick/daily/issues/347)
104. [如何用jQuery来创建插件？](https://github.com/pwstrick/daily/issues/348)
105. [两次输出各是什么？](https://github.com/pwstrick/daily/issues/729)
```javascript
     for (var i = 0; i < 3; i++) {
       setTimeout(() => console.log(i), 1)
     }
     
     for (let i = 0; i < 3; i++) {
       setTimeout(() => console.log(i), 1)
     }
```

106. [下面代码的输出是什么？](https://github.com/pwstrick/daily/issues/737)
```javascript
function Person(firstName, lastName) {
  this.firstName = firstName;
  this.lastName = lastName;
}

const lydia = new Person("Lydia", "Hallie");
const sarah = Person("Sarah", "Smith");

console.log(lydia);
console.log(sarah);
```

107. [当我们这样做时会发生什么？](https://github.com/pwstrick/daily/issues/738)
```javascript
function bark() {
  console.log("Woof!");
}
bark.animal = "dog";
```

108. [事件传播的三个阶段是什么？](https://github.com/pwstrick/daily/issues/739)
109. [所有对象都有原型，这句描述是否正确？](https://github.com/pwstrick/daily/issues/740)

110. [下面代码的输出是什么？](https://github.com/pwstrick/daily/issues/741)
```javascript
let number = 0;
console.log(number++);
console.log(++number);
console.log(number);
```

111. [下面代码的输出是什么？](https://github.com/pwstrick/daily/issues/743)
```javascript
function checkAge(data) {
  if (data === { age: 18 }) {
    console.log("You are an adult!");
  } else if (data == { age: 18 }) {
    console.log("You are still an adult.");
  } else {
    console.log(`Hmm.. You don't have an age I guess`);
  }
}
checkAge({ age: 18 });
```

112. [下面代码的输出是什么？](https://github.com/pwstrick/daily/issues/745)
```javascript
function getAge() {
  "use strict";
  age = 21;
  console.log(age);
}
getAge();
```

113. [cool_secret可以访问多长时间？](https://github.com/pwstrick/daily/issues/746)
```javascript
sessionStorage.setItem("cool_secret", 123);
```

114. [JavaScript全局执行上下文为你创建了全局对象和this关键字，这句话是否正确？](https://github.com/pwstrick/daily/issues/749)
115. [单击按钮时event.target指向的是哪个元素？](https://github.com/pwstrick/daily/issues/753)
```html
<div onclick="console.log('first div')">
  <div onclick="console.log('second div')">
    <button onclick="console.log('button')">
      Click!
    </button>
  </div>
</div>
```

116. [单击下面的html片段打印的内容是什么？](https://github.com/pwstrick/daily/issues/754)
```html
<div onclick="console.log('div')">
  <p onclick="console.log('p')">
    Click here!
  </p>
</div>
```

117. [下面这些值哪些是假值？](https://github.com/pwstrick/daily/issues/757)
```javascript
0;
new Number(0);
("");
(" ");
new Boolean(false);
undefined;
```

118. [前端的requestAnimationFrame了解吗？有使用过吗？请说一下使用场景。](https://github.com/pwstrick/daily/issues/768)
119. [对前后端跨域可以说一下吗？有碰到过跨域问题吗？如何解决跨域的？](https://github.com/pwstrick/daily/issues/769)
120. [闭包为什么会造成内存泄漏？](https://github.com/pwstrick/daily/issues/784)
121. [请讲一下JavaScript的垃圾回收机制。](https://github.com/pwstrick/daily/issues/785)
122. [求一个对象的层级数，用递归和循环分别实现。](https://github.com/pwstrick/daily/issues/799)
123. [实现下面这道题中的machine函数。](https://github.com/pwstrick/daily/issues/800)
```javascript
function machine() {
    
}
machine('ygy').execute() 
// start ygy
machine('ygy').do('eat').execute(); 
// start ygy
// ygy eat
machine('ygy').wait(5).do('eat').execute();
// start ygy
// wait 5s（这里等待了5s）
// ygy eat
machine('ygy').waitFirst(5).do('eat').execute();
// wait 5s
// start ygy
// ygy eat
```

124. [lodash和ramda的区别是什么？](https://github.com/pwstrick/daily/issues/809)
125. [字符串和new String出来的字符串有啥区别？](https://github.com/pwstrick/daily/issues/810)
126. [JS如何判断网页中图片加载成功或者失败？](https://github.com/pwstrick/daily/issues/822)
127. [递归和迭代的区别是什么，各有什么优缺点？](https://github.com/pwstrick/daily/issues/823)
128. [实现一个类型判断函数，需要鉴别出基本类型、function、null、NaN、数组、对象？](https://github.com/pwstrick/daily/issues/825)
129. [什么是节流和抖动？](https://github.com/pwstrick/daily/issues/827)
130. [深拷贝和浅拷贝有什么区别？](https://github.com/pwstrick/daily/issues/828)
131. [如何实现对一个DOM元素的深拷贝，包括元素的绑定事件？](https://github.com/pwstrick/daily/issues/833)
132. [用代码模拟出apply()、call()和bind()三个函数。](https://github.com/pwstrick/daily/issues/854)
133. [用代码模拟instanceof运算符。](https://github.com/pwstrick/daily/issues/855)
134. [实现一个简单的路由。](https://github.com/pwstrick/daily/issues/856)
135. [封装鼠标拖拽的功能。](https://github.com/pwstrick/daily/issues/857)
136. [如何让两个非常大的数字相加？](https://github.com/pwstrick/daily/issues/859)
137. [宏任务和微任务是指什么？](https://github.com/pwstrick/daily/issues/939)
138. [实现预加载和懒加载。](https://github.com/pwstrick/daily/issues/945)
139. [如何用Ajax实现大文件上传？](https://github.com/pwstrick/daily/issues/958)
140. [如何用JavaScript实现两个大数的相加？](https://github.com/pwstrick/daily/issues/963)
141. [ES6的模块和CommonJS模块的对比](https://github.com/pwstrick/daily/issues/964)
142. [模拟Object.create()方法。](https://github.com/pwstrick/daily/issues/967)
143. [实现JSON.parse()方法。](https://github.com/pwstrick/daily/issues/968)
144. [setTimeout背后的原理是怎么样的？](https://github.com/pwstrick/daily/issues/969)
145. [如果实现前端截图？](https://github.com/pwstrick/daily/issues/970)
146. [setTimeOut 和 setInterval 底层有哪些区别？](https://github.com/pwstrick/daily/issues/971)
147. [在CORS跨域请求时，什么情况下会发两次请求？](https://github.com/pwstrick/daily/issues/972)
148. [在CORS跨域请求时，需要携带cookie，得做哪些配置？](https://github.com/pwstrick/daily/issues/973)
149. [如何实现并发请求？](https://github.com/pwstrick/daily/issues/977)

## 思维导图
![JavaScript](https://github.com/pwstrick/daily/blob/master/assets/img/mind/JavaScript.png)
