# Daily-Interview-Question

工作日每天一道前端大厂面试题，祝大家天天进步，一年后会看到不一样的自己。

欢迎 PR 你认为不错的面试题，欢迎在 Issue 区留下你的答案，共同参与这个伟大的项目。



## 今日面试题

2019-03-14

> 第 34 题：对于浏览器缓存:有的是存在硬盘中(from disk),有的是存在内存中(from memory),这个依据是什么？具体可以在浏览器控制台`Network`选项卡中查看请求

欢迎在 Issue 区留下你的答案。


## 本周汇总

2019-03-14

> 第 33 题：下面的代码打印什么内容，为什么？

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```
解析：[第 33 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/48)

2019-03-13

> 第 32 题：Virtual DOM 真的比操作原生 DOM 快吗？谈谈你的想法。

解析：[第 32 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/47)


2019-03-12

> 第 31 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法。

```js
for (var i = 0; i< 10; i++){
	setTimeout(() => {
		console.log(i);
    }, 1000)
}
```

解析：[第 31 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/43)


2019-03-11

> 第 30 题：请把两个数组 ['A1', 'A2', 'B1', 'B2', 'C1', 'C2', 'D1', 'D2'] 和 ['A', 'B', 'C', 'D']，合并为 ['A1', 'A2', 'A', 'B1', 'B2', 'B', 'C1', 'C2', 'C', 'D1', 'D2', 'D']。

解析： [第 30 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/39)



## 历史汇总

-   [前端面试题及答案汇总](https://github.com/Advanced-Frontend/Daily-Interview-Question/blob/master/datum/summary.md)



## 交流

进阶系列文章汇总如下，内有优质前端资料，觉得不错点个 star。

> [https://github.com/yygmind/blog](https://github.com/yygmind/blog)

我是木易杨，网易高级前端工程师，跟着我**每周重点攻克一个前端面试重难点**。接下来让我带你走进高级前端的世界，在进阶的路上，共勉！

如果你想加群讨论每期面试知识点，公众号回复「 [加群]() 」即可 ![image](https://github.com/yygmind/blog/raw/master/images/weixin_re.png)
