# xq_navbar
简单实现依赖于jQuery自定义快捷的炫酷导航条效果,样式效果完全自定义。^_^

来一起感受它的魅力吧！

<h3>1.技术点</h3>

两个个鼠标事件：

onmouseover：鼠标移到指定对象上时触发；

onmouseout：鼠标离开指定时触发；

<h3>2.先来看看它的执行效果吧。（请用电脑）<h3>

https://topqiang.github.io/xq_navbar/

<h3>3.迫不及待想试一试了。</h3>

< link rel="stylesheet" href="css/xq_navbar.css"/>

< link rel="stylesheet" href="css/xq.css"/>//不采用beat动画 ，可以不引入

然后在body尾部引入
< script src="js/jquery.min.js" type="text/javascript"></script>

< script src="js/xq_navbar.js" type="text/javascript"></script>


  <code>
  
    <div class="xq_bag" id="bar5">//可以自定义其大小
			<ul class="xq_navbar">
				<li class="xq_navli"><a href="#">java</a></li>
				<li class="xq_navli"><a href="#">php</a></li>
				<li class="xq_navli"><a href="#">c#</a></li>
				<li class="xq_navli"><a href="#">photoshop</a></li>
				<li class="xq_navli"><a href="#">c++</a></li>
				<li class="xq_navli"><a href="#">html</a></li>
				<li class="xq_navli"><a href="#">javascript</a></li>
			</ul>
		</div>
		
  </code>
<h3>4.那么配置参数都有那些呢？</h3>
<code>

    var defaults = {
			"bgcolor"	: "#38927a",		    //导航条颜色
			"type"		: "line",	          //定义导航类型    下划线 underline 上划线overline 双划线line 块级背景block 
			"liwidth"	: "avg",		        //设置导航项的宽度类型 auto：自动  ， avg：评分， 30：指定具体宽度 
			"hcolor"	: "rgba(255,0,0,0.8)"//指定每一个导航项的颜色。不指定或指定不够默认 #ccc；统一颜色可直接传入颜色值.也可以["blue","rgb(10,100,100)","red","pink","green","rgba(23,234,22,1)","rgb(230,230,230)"]
		}
		
</code>

<h3>5.怎么启动呢？</h3>
页面加载完成后即可调用该插件，传入你想要效果的参数
 $("#bar5").xq_navbar({
      "type":"block",
      "liwidth":"avg",
      "bgcolor":"#000",
      "hcolor":["blue","rgb(10,100,100)","red","pink","green","rgba(23,234,22,1)","rgb(230,230,230)"]
    });


再次特请各位大牛指出不足。
跪拜！跪拜！
