<!doctype html><html>         <head>               <meta http-equiv="Content-Type" content="text/html;charset=utf-8">                  <title>html模板</title>      <meta name="Keywords" content="关键词，关键词">      <meta name="description" content="">                  <!--css,js-->      <!--css:层叠样式表，一件美丽的衣服-->      <style type="text/css">       body{height:2000px;margin:0;padding:0;font-size:12px;font-family:"微软雅黑";color:#666;}       .nav{width:1210px;height:40px;background:#E4393C; margin:200px auto;}                .nav ul li{float:left;line-height:40px;}             .nav ul li a{font-size:14px;color:#fff;text-decoration:none;padding:0 30px;font-weight:bold;display:block;}         .nav ul li .n-sel{background:#A40000;}       .nav ul li a:hover{background:#A40000;}       .nav ul .n_all{width:210px;}       .nav ul .n_all a:hover{background:#E4393C;text-decoration:underline;}      </style>          </head><body>   <a src="#" target="content"></a>   <h1>HTML标签 - 无序列表</h1>   <p>无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。
     无序列表始 ul 标签；
     每个列表项始于 li （列表项内部可以使用段落、换行符、图片、链接以及其他列表等）。
     具体事例:</p>   <ul>     <li>我是列表项 </li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>
   </ul>   <h1>HTML标签 - 有序列表</h1>   <p>和无序列表一样，有序列表是一列项目，列表项目使用数字进行标记。
    有序列表始于 ol 标签；
    每个列表项始于li 标签（列表项内部可以使用段落、换行符、图片、链接以及其他列表等）。</p>   <ol>     <li>我是列表项 </li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>     <li>我是列表项</li>
   </ol>   <h1>HTML标签 - 定义列表：</h1>
   自定义列表不仅仅是一列项目，而是项目及其注释的组合。
   自定义列表以 dl 标签开始；
   每个自定义列表项以 dt 开始；
   每个自定义列表项的定义以 dd>开始。
   （定义列表的列表项内部可以使用段落、换行符、图片、链接以及其他列表等）
    <dl>      <dt>自定列表项1</dt>      <dd>列表项的定义1</dd>      <dt>自定列表项2</dt>      <dd>列表项的定义2</dd>    </dl>  <h1>HTML标签 - 列表标签的应用</h1>  <p><1> 不同类型的无序列表： type=“disc/circle/square”项目符号列表 ;<br>  <2> 不同类型的有序列表： type=“默认数字/大写字母A/小写字母a/大写罗马字母I/小写罗马字母i” 列表 ;<br>  <3> 嵌套列表： ul li(中嵌套ul li) ;<br>  <4> 2级嵌套列表： ul li(中嵌套ul li<中嵌套ul li>) ;<br>  <5> 定义列表；</p>   <ul>     <li type="disc">我是列表项 </li>     <li type="circle">我是列表项</li>     <li type="square">我是列表项</li>   </ul>   <ol>     <li  type="A">我是列表项 </li>     <li type="A">我是列表项</li>     <li type="A">我是列表项</li>     <li type="a">我是列表项</li>     <li type="a">我是列表项</li>     <li type="a">我是列表项</li>
   </ol>   <ol>     <li type="I">我是列表项 </li>     <li type="I">我是列表项</li>     <li type="I">我是列表项</li>     <li type="i">我是列表项</li>     <li type="i">我是列表项</li>     <li type="i">我是列表项</li>
   </ol>    <ul>     <li type="disc">我是列表项1                      <ul>           <li>我是列表项              <ul>               <li>我是列表项 </li>               <li>我是列表项</li>               <li>我是列表项</li>                  </ul>            </li>           <li>我是列表项</li>           <li>我是列表项</li>              </ul>      </li>     <li>我是列表项</li>     <li>我是列表项</li>        </ul>
   <div class="nav">     <ul>       <li><a href="#">全部商品分类</a></li>       <li><a href="#">首页</a></li>       <li><a href="#">服装城</a></li>       <li><a href="#">食品</a></li>       <li><a href="#">团购</a></li>       <li><a href="#">金融</a></li>       <li><a href="#">夺宝岛</a></li>       <li><a href="#">闪现</a></li>
     </ul>   </div>
        
</html></html>
