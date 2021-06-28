# heading1...6的字体高度相对于body默认字体高度的倍数

### 一般heading 1 - heading 6的font-size都是相对于body字体高度的自动变大或变小，不需要特意注明字体大小。

## 打开实验文件

单击右方的[<h1> to <h6> + body](https://codepen.io/quanbinn/pen/BaRBgeE), 浏览器里会打开一个新的页面，里面有下面的代码段，如下图所示。

```html
<h1>这是heading 1</h1>
<h2>这是heading 2</h2>
<h3>这是heading 3</h3>
<h4>这是heading 4</h4>
<h5>这是heading 5</h5>
<h6>这是heading 6</h6>

<p>普通内容</p>
<p>普</p>
```

### 上述html的文件经过chrome浏览器渲染之后，各个元素的绝对高度和之间的相对倍数如下图所示。

- p: 21.48 px ~= 1.34 rem
- h1: 42.22 px ~= 2.63 rem，p之类的body字体的**1.96倍**；
- h2: 31.11 px ~= 1.94 rem，p之类的body字体的**1.45倍**；
- h3: 25.19 px ~= 1.57 rem，p之类的body字体的**1.17倍**；  
- h4: 21.48 px ~= 1.34 rem，p之类的body字体的**1倍**； 
- h5: 17.78 px ~= 1.11 rem，p之类的body字体的**0.83倍**； 
- h6: 15.56 px ~= 0.97 rem，p之类的body字体的**0.72倍**； 

## Reference

1. [HTML <h1> to <h6> Tags](https://www.w3schools.com/tags/tag_hn.asp)
