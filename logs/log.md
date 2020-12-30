### day 1
2020.12.09 星期三

学习vue3响应式原理，看Jocky老师视频 读vue3响应式源码  [深入理解 Vue3 Reactivity API](https://zhuanlan.zhihu.com/p/146097763) 、 [vue3.0 响应式原理(超详细)](https://juejin.cn/post/6858899262596448270)

### day 2
2020.12.10 星期四

学习vue3响应式原理，重新看Jocky老师响应式原理视频

### day 3
2020.12.11 星期五

学习github Actions  [github线上构建](https://p3terx.com/archives/github-actions-started-tutorial.html) 、 [github自动化部署](https://frostming.com/2020/04-26/github-actions-deploy/)  ， 看Vue2源码（Observer）

### day 4
2020.12.12 星期六

学习vue2响应式原理，读vue2源码，看黄轶老师响应式原理视频，  数据初始化（defineReactive，Observer）→ get内进行依赖收集（Dep deps收集Watcher（renderWatcher、UserWatcher） ）→ set时进行派发更新（遍历以来deps内的Watcher执行Watcher.run）→更新时的事件调度 queue nextTick

### day 5
2020.12.13 星期日

休息

### day6
2020.12.14 星期一

学习vue2响应式原理源码 [Vue2.0 源码阅读：响应式原理](http://zhouweicsu.github.io/blog/2017/03/07/vue-2-0-reactivity/) 学习js执行机制Event Loop以及MicroTask MacroTask [JavaScript 运行机制详解：再谈Event Loop](http://www.ruanyifeng.com/blog/2014/10/event-loop.html) 、 [微任务、宏任务、同步、异步、Promise、Async、await](https://www.cnblogs.com/jiangyuzhen/p/11064408.html)  结合vue2源码理解$nextTick，读vue派发更新源码 理解scheduler，queue 读vue2数据驱动源码（mount，render），看黄轶老师视频

### day7
2020.12.15 星期二

看vue2源码 看黄轶老师视频学习vue2的数据驱动原理（new Vue的render 和组件的render Vue.extend  &#95;update  &#95;&#95;patch&#95;&#95; ）

### day8
2020.12.16 星期三

看黄轶老师视频，学习vue2组件dom更新原理 初步了解updateChildren函数

### day9
2020.12.17 星期四

深入了解vue DOM更新时 updateChild Diff算法  [【Vue原理】Diff - 源码版 之 Diff 流程](https://juejin.cn/post/6844903961837699079)  看vue3 diff算法源码，与vue2 diff算法对比阅读 搞懂dom重新渲染流程 了解[最长递增子序列](https://zh.wikipedia.org/wiki/%E6%9C%80%E9%95%BF%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97) 在vue3 diff算法的应用 学习vue3 createVnode函数（doing）

### day10
2020.12.18 星期五

搞清楚vue3中的diff算法，理解大体流程， 看黄轶老师视频学习vue2的compiler过程

### day11
2020.12.19 星期六

休息

### day12
2020.12.20 星期日

休息

### day13
2020.12.21 星期一

休息

### day14
2020.12.22 星期二

看黄轶老师视频学习vue2的compile 编译大致分为三大步骤  parseHtml optimize codeGenerate 

### day15
2020.12.23 星期三

温习vue3 从createApp到组件组件挂载过程（看源码） 尝试读vue3 compiler相关源码发现看不明白， 学习Typescript相关内容 大致搞懂泛型概念 看视频学习（ts+vue3知乎）

### day16
2020.12.24 星期四

学习vue3新特性（Teleport Suspense） 了解组件自定义事件在tsx中的写法以及为何子组件emit时写法 当事件不在子组件props定义时会引起适用方报错 [@vue/babel-plugin-jsx issues#236](https://github.com/vuejs/jsx-next/issues/236)

### day17
2020.12.25 星期五

看视频学习（ts+vue3知乎）跟随老师编写vue3在实际应用时代码 了解在vue3 tsx中父组件传值 props emit attrs等

### day18
2020.12.26 星期六

休息

### day19
2020.12.27 星期日

休息

### day20
2020.12.28 星期一

学习vuex vue-router 学习tapable包的 SyncHook SyncBailHook SyncWaterfallHook SyncLoopHook

### day21
2020.12.29 星期二

学习tapable异步钩子 跟随zf老师手写webpack