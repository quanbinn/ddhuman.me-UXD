# 用flex实现image的自适应布局

```css
.textOverImage {
    			position: relative; 
    			text-align: center; 
    			color: white; 
    			font-size: 5.5rem; 
    			flex:33%
}

.centered {
    	   position: absolute; 
    	   top: 50%;	
    	   left: 50%; 
    	   transform: translate(-50%, -50%);
}

@media (max-width: 1080px) {
  .textOverImage {
      			  flex:50%
                 }
}
```

```html
<html>
  <head>
    <title>首页</title>
    <link rel="stylesheet" type="text/css" href="/public/css/style.css">
  </head>

  <body>
	<nav>
	  <a href="/user/registerForm" class="">注册</a> | 
	  <a href="/user/loginForm" class="">登录</a>	
	</nav>
	<div style="display:flex; flex-wrap:wrap">
		<div class="textOverImage">
		  <img src="/public/image/实体学习.jpg" alt="实体学习" style="width:100%;">
		  <span class="centered">实体学习</span>
		</div>
		<div class="textOverImage">
		  <img src="/public/image/拆分工作.jpg" alt="拆分工作" style="width:100%;">
		  <span class="centered">拆分工作</span>
		</div>
		<div class="textOverImage">
		  <img src="/public/image/极速购物.jpg" alt="极速购物" style="width:100%;">
		  <span class="centered">极速购物</span>
		</div>
		<div class="textOverImage">
		  <img src="/public/image/防卫锻炼.jpg" alt="防卫锻炼" style="width:100%;">
		  <span class="centered">防卫锻炼</span>
		</div>
		<div class="textOverImage">
		  <img src="/public/image/健康饮食.jpg" alt="健康饮食" style="width:100%;">
		  <span class="centered">健康饮食</span>
		</div>
		<div class="textOverImage">
		  <img src="/public/image/防病防险.jpg" alt="防病防险" style="width:100%;">
		  <span class="centered">防病防险</span>
		</div>
	</div>
  </body>
</html>
```

## Reference

1. **[Flex 布局语法教程](https://www.runoob.com/w3cnote/flex-grammar.html)**
1. **[Image Text](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_text)**
1. [.class, #id from CSS](https://en.wikipedia.org/wiki/CSS)
2. [Responsive web design from Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design)
3. [*.class* Selector](https://www.w3schools.com/cssref/sel_class.asp)
4. [#*id* Selector](https://www.w3schools.com/cssref/sel_id.asp)
5. [What is Responsive Web Design?](https://www.w3schools.com/whatis/whatis_responsive.asp)
6. [W3.CSS Framework](https://www.w3schools.com/w3css/default.asp)

