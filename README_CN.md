[ENGLISH](./README.md)

<h1 align="center">DataV</h1>

<p align="center">
    <a href="https://github.com/jiaming743/datav/blob/master/LICENSE">
      <img src="https://img.shields.io/github/license/jiaming743/datav.svg" alt="LICENSE" />
    </a>
    <a href="https://www.npmjs.com/package/@jiaminghi/data-view">
      <img src="https://img.shields.io/npm/v/@jiaminghi/data-view.svg" alt="LICENSE" />
    </a>
</p>

## DataV是干什么的?

* DataV是一个基于**Vue**的数据可视化组件库.
* 提供用于提升页面视觉效果的**SVG**边框和装饰.
* 提供常用的**图表**如折线图等.
* 飞线图/轮播表等其他组件.

### npm安装

```shell
$ npm install @jiaminghi/data-view
```

### 使用

```js
import Vue from 'vue'
import DataV from '@jiaminghi/data-view'

Vue.use(DataV)

// 按需引入
import { borderBox1 } from '@jiaminghi/data-view'
Vue.use(borderBox1)
```

详细文档及示例请移步[HomePage](http://datav.jiaminghi.com).