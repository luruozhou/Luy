![](https://github.com/Foveluy/Luy/blob/master/art/luy.png?raw=true)

# Luy，一个类 React 框架

所谓类`React`框架就是**和 React 用法一模一样**的框架。我的目标是，缔造一个和 React 一摸一样的框架。

## 跑 fiber 架构

```
git clone https://github.com/Foveluy/Luy.git
cd Luy
npm i --save-dev
npm run start
```

## 以下是 React 15 版本的

和`React`一模一样，我们来看一个最简单的实例

```javascript
import React from 'luy'
import ReactDOM from 'luy'

class Luy extends React.Component {
  render() {
    return <div>Hello,Luy!</div>
  }
}

ReactDOM.render(<Luy />, document.getElementById('root'))
```

## 性能测试

* [Luy 第一版性能测试](http://htmlpreview.github.io/?https://github.com/215566435/Luy/blob/master/performance/luy/index.html)
* [react 官方性能测试](http://htmlpreview.github.io/?https://github.com/215566435/Luy/blob/master/performance/react/index.html)
