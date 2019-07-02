文档的基本结构：
文档类型声明
文档头
文档体
文档元素
HTML基本元素：标记、元素、内容、属性
HTML注释： <!--    --->
HTMl图片
<img src=”http://dsadasdasf/152521/422852/22 “/>   //网上的链接
<img src=”a.jag” width=”100” height=”200” />
<img src=”img/a.jag” width=”100” height=”200” />    //相对于当前目录所在的路径找名为a.jpgd 图片	
<img src=”/img/a.jag” width=”100” height=”200”alt=”这里是加载失败时的替换文字” />     //绝对路径，无论图片在web服务器的那个路径下，都会在web 的根目录下去寻找
一般情况下，必须加alt属性	
HTML超链接
文本外链接：
	<a href=”http://weibo.com/simbasong”>宋波微博</a>
<a href=”http://weibo.com/simbasong” target=”_blank”>宋波微博</a>  // target=”_blank” 含义为当前所在的网页被保留，并尝试打开一个新的网页
文档超链接的含义就是实现从一个文档到另一个文档的跳转。
文档内导航：
<a href=”#faq”>常见问题</a>  //当点击常见问题时，会实现文档类导航跳转的过程。相当于滚动鼠标找到所需要制定的id。
<a href=”#”>回顶部</a>
<a href=”http://abc.com/course/202#faq”>常见问题</a> //当点击常见问题的时候，html首先会跳转到http所在的文件找到202，然后立刻去寻找faq所在的位置。
HTML的表单元素
<form>元素为用户输入输入创建HTML表单，用于向服务器提交数据。
如：
<form action="/course/reg.do" method="post" enctype="multipart/form-data">
<p>姓名：<input type="text" /></p>    <!—input和textarea的区别在于input只能输入一行
<p>简介：<textarea></textarea></p>      内容，而textarea允许输入多行内容-->
<p>简介附件：<input type="file" /></p>
<p><input type="submit" value="报名提交"></p>
</form>
HTML标题、段落和文本格式化
<h1> <h2><h3> <h4><h5> <h6>代表各级标题，并且字体依次减小
<p>代表段落元素，代表一段文本
<br>代表HTML的换行
<hr>代表一条水平的分割线
<b>代表加粗文本
<i>代表斜体文本
<strong>代表一段比较重要的文本，相当于加粗
<em>代表一段需要强调的文本，想当于给文本加上斜体
<small>代表使文字变小
<del>代表在文本的中间加上一条线，代表删除，如：
<ins>代表在文字的下方加上一条下划线
HTML list
Unordered list 无序列表
<ul>
<li>Item</li>
<li>Item</li>
</ul>
Ordered list  有序列表
<ol>
<li>Item</li>
<li>Item</li>
</ol>
<li>中除了存放文本以外，还可以存放<ul>或者<ol>元素
HTML Table
基本的Table tags
<table>
<caption>
<tr>table row
<th>table head
<td>table data
如案例（此处只提供HTML部分）：
<table>
<tr>
<th>周一</th>
<th>周二</th>
<th>周三</th>
<th>周四</th>
<th>周五</th>
<th>周六</th>
<th>周日</th>
</tr>
<tr>
<td>语文</td>
<td>数学</td>
<td>英语</td>
<td>C语言</td>
<td>java</td>
</tr>
</table>
