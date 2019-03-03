<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [前端面试题及答案汇总](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%8A%E7%AD%94%E6%A1%88%E6%B1%87%E6%80%BB)
  - [第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么](#%E7%AC%AC-1-%E6%9C%9F%E5%86%99-react--vue-%E9%A1%B9%E7%9B%AE%E6%97%B6%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%9C%A8%E7%BB%84%E4%BB%B6%E4%B8%AD%E5%86%99-key%E5%85%B6%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?](#%E7%AC%AC-2-%E6%9C%9F1-2-3mapparseint-what--why-)
  - [第 3 期：什么是防抖和节流？有什么区别？如何实现？](#%E7%AC%AC-3-%E6%9C%9F%E4%BB%80%E4%B9%88%E6%98%AF%E9%98%B2%E6%8A%96%E5%92%8C%E8%8A%82%E6%B5%81%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？](#%E7%AC%AC-4-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B-setmapweakset-%E5%92%8C-weakmap-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？](#%E7%AC%AC-5-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](#%E7%AC%AC-6-%E6%9C%9F%E8%AF%B7%E5%88%86%E5%88%AB%E7%94%A8%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%8B%B7%E8%B4%9D%E5%87%BD%E6%95%B0)
  - [第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？](#%E7%AC%AC-7-%E6%9C%9Fes5es6-%E7%9A%84%E7%BB%A7%E6%89%BF%E9%99%A4%E4%BA%86%E5%86%99%E6%B3%95%E4%BB%A5%E5%A4%96%E8%BF%98%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
  - [第 8 期：setTimeout、Promise、Async/Await 的区别](#%E7%AC%AC-8-%E6%9C%9Fsettimeoutpromiseasyncawait-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 9 期：Async/Await 如何通过同步的方式实现异步](#%E7%AC%AC-9-%E6%9C%9Fasyncawait-%E5%A6%82%E4%BD%95%E9%80%9A%E8%BF%87%E5%90%8C%E6%AD%A5%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0%E5%BC%82%E6%AD%A5)
  - [第10期：异步笔试题](#%E7%AC%AC10%E6%9C%9F%E5%BC%82%E6%AD%A5%E7%AC%94%E8%AF%95%E9%A2%98)
  - [第11题：算法手写题](#%E7%AC%AC11%E9%A2%98%E7%AE%97%E6%B3%95%E6%89%8B%E5%86%99%E9%A2%98)
  - [第12题：JS 异步解决方案的发展历程以及优缺点。](#%E7%AC%AC12%E9%A2%98js-%E5%BC%82%E6%AD%A5%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88%E7%9A%84%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%E4%BB%A5%E5%8F%8A%E4%BC%98%E7%BC%BA%E7%82%B9)
  - [第13题：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？](#%E7%AC%AC13%E9%A2%98promise-%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%E6%98%AF%E5%90%8C%E6%AD%A5%E6%89%A7%E8%A1%8C%E8%BF%98%E6%98%AF%E5%BC%82%E6%AD%A5%E6%89%A7%E8%A1%8C%E9%82%A3%E4%B9%88-then-%E6%96%B9%E6%B3%95%E5%91%A2)
  - [第14题：情人节福利题，如何实现一个 new](#%E7%AC%AC14%E9%A2%98%E6%83%85%E4%BA%BA%E8%8A%82%E7%A6%8F%E5%88%A9%E9%A2%98%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-new)
  - [第15题：简单讲解一下http2的多路复用](#%E7%AC%AC15%E9%A2%98%E7%AE%80%E5%8D%95%E8%AE%B2%E8%A7%A3%E4%B8%80%E4%B8%8Bhttp2%E7%9A%84%E5%A4%9A%E8%B7%AF%E5%A4%8D%E7%94%A8)
  - [第16题：谈谈你对TCP三次握手和四次挥手的理解](#%E7%AC%AC16%E9%A2%98%E8%B0%88%E8%B0%88%E4%BD%A0%E5%AF%B9tcp%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%92%8C%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第17题：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态](#%E7%AC%AC17%E9%A2%98ab-%E6%9C%BA%E5%99%A8%E6%AD%A3%E5%B8%B8%E8%BF%9E%E6%8E%A5%E5%90%8Eb-%E6%9C%BA%E5%99%A8%E7%AA%81%E7%84%B6%E9%87%8D%E5%90%AF%E9%97%AE-a-%E6%AD%A4%E6%97%B6%E5%A4%84%E4%BA%8E-tcp-%E4%BB%80%E4%B9%88%E7%8A%B6%E6%80%81)
  - [第18题：React 中 setState 什么时候是同步的，什么时候是异步的？](#%E7%AC%AC18%E9%A2%98react-%E4%B8%AD-setstate-%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E6%98%AF%E5%90%8C%E6%AD%A5%E7%9A%84%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E6%98%AF%E5%BC%82%E6%AD%A5%E7%9A%84)
  - [第19题：React setState 笔试题，下面的代码输出什么？](#%E7%AC%AC19%E9%A2%98react-setstate-%E7%AC%94%E8%AF%95%E9%A2%98%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->





## 前端面试题及答案汇总



### 第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么

解析：[第一题：key的作用是为了在diff算法执行时更快的找到对应的节点，提高diff速度。](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)



### 第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?

解析：[第二题：['1', '2', '3'].map(parseInt) 解析](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)



### 第 3 期：什么是防抖和节流？有什么区别？如何实现？

解析：[第三题：节流和防抖的个人见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)



### 第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？

解析：[第四题：Set、Map、WeakSet 和 WeakMap](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)



### 第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？

解析：[关于第五题我的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)



### 第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？

解析：[第六题 实现深度拷贝](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/10)



### 第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？

解析：[第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？解答与一个疑惑](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/20)



### 第 8 期：setTimeout、Promise、Async/Await 的区别

欢迎在 Issue 区留下你的答案。



### 第 9 期：Async/Await 如何通过同步的方式实现异步

欢迎在 Issue 区留下你的答案。



### 第10期：异步笔试题

> 请写出下面代码的运行结果

```js
async function async1() {
    console.log('async1 start');
    await async2();
    console.log('async1 end');
}
async function async2() {
    console.log('async2');
}
console.log('script start');
setTimeout(function() {
    console.log('setTimeout');
}, 0)
async1();
new Promise(function(resolve) {
    console.log('promise1');
    resolve();
}).then(function() {
    console.log('promise2');
});
console.log('script end');
```

解析：[关于第10题的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/7)



### 第11题：算法手写题

> 已知如下数组：
>
> var arr = [ [1, 2, 2], [3, 4, 5, 5], [6, 7, 8, 9, [11, 12, [12, 13, [14] ] ] ], 10];
>
> 编写一个程序将数组扁平化去并除其中重复部分数据，最终得到一个升序且不重复的数组

解析：[第11题：将数组扁平化并去除其中重复数据，最终得到一个升序且不重复的数组](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/8)



### 第12题：JS 异步解决方案的发展历程以及优缺点。

解析：[第十二题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/11)



### 第13题：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？

解析：[关于第13题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/19)



### 第14题：情人节福利题，如何实现一个 new

解析：[14题 情人节快乐！](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/12)



### 第15题：简单讲解一下http2的多路复用

解析：[第15题：简单讲解一下http2的多路复用](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/14)



### 第16题：谈谈你对TCP三次握手和四次挥手的理解

解析：[关于第16题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/15)



### 第17题：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态

> 如果A 与 B 建立了正常连接后，从未相互发过数据，这个时候 B 突然机器重启，问 A 此时处于 TCP 什么状态？如何消除服务器程序中的这个状态？（超纲题，了解即可）

解析：[关于17题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/21)



### 第18题：React 中 setState 什么时候是同步的，什么时候是异步的？

解析：[第18题：React 中 setState 什么时候是同步的，什么时候是异步的？](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/17)



### 第19题：React setState 笔试题，下面的代码输出什么？

```js
class Example extends React.Component {
  constructor() {
    super();
    this.state = {
      val: 0
    };
  }
  
  componentDidMount() {
    this.setState({val: this.state.val + 1});
    console.log(this.state.val);    // 第 1 次 log

    this.setState({val: this.state.val + 1});
    console.log(this.state.val);    // 第 2 次 log

    setTimeout(() => {
      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 第 3 次 log

      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 第 4 次 log
    }, 0);
  }

  render() {
    return null;
  }
};
```

解析：[关于第19题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/18)



### 第 20 题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？

解析：[第20题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/22)



### 第 21 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣

> Object.prototype.toString.call() 、 instanceof 以及 Array.isArray() 

解析：[第21题：介绍它们之间的区别和优劣](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/23)



### 第 22 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化

解析：[第22题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/24)



### 第 23 题：介绍下观察者模式和订阅-发布模式的区别，各自适用于什么场景

解析：[第 23 题：介绍下观察者模式和订阅\-发布模式的区别，各自适用于什么场景](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/25)



### 第24题：聊聊 Redux 和 Vuex 的设计思想

欢迎在 Issue 区留下你的答案。

