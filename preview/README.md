
	    <html>
	      <head>
				  <meta http-equiv="content-type" content="text/html; charset=utf-8" />
	        <title>README</title>
					
					<link href="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/style/github-bf51422f4bb36427d391e4b75a1daa083c2d840e.css" media="all" rel="stylesheet" type="text/css"/>
					<link href="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/style/github2-d731afd4f624c99a4b19ad69f3083cd6d02b81d5.css" media="all" rel="stylesheet" type="text/css"/>
					<link href="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/css/zTreeStyle/zTreeStyle.css" media="all" rel="stylesheet" type="text/css"/>
			
				  <style>
					pre {
					    counter-reset: line-numbering;
					    border: solid 1px #d9d9d9;
					    border-radius: 0;
					    background: #fff;
					    padding: 0;
					    line-height: 23px;
					    margin-bottom: 30px;
					    white-space: pre;
					    overflow-x: auto;
					    word-break: inherit;
					    word-wrap: inherit;
					}

					pre a::before {
					  content: counter(line-numbering);
					  counter-increment: line-numbering;
					  padding-right: 1em; /* space after numbers */
					  width: 25px;
					  text-align: right;
					  opacity: 0.7;
					  display: inline-block;
					  color: #aaa;
					  background: #eee;
					  margin-right: 16px;
					  padding: 2px 10px;
					  font-size: 13px;
					  -webkit-touch-callout: none;
					  -webkit-user-select: none;
					  -khtml-user-select: none;
					  -moz-user-select: none;
					  -ms-user-select: none;
					  user-select: none;
					}

					pre a:first-of-type::before {
					  padding-top: 10px;
					}

					pre a:last-of-type::before {
					  padding-bottom: 10px;
					}

					pre a:only-of-type::before {
					  padding: 10px;
					}
			
					.highlight { background-color: #ffffcc } /* RIGHT */
					</style>
	      </head>
	      <body>
				  <div>
							<div style='width:25%;'>
									<ul id="tree" class="ztree" style='width:100%'>
		
									</ul>
							</div>
			        <div id='readme' style='width:70%;margin-left:20%;'>
			          	<article class='markdown-body'>
			            	<style>.highlight .hll { background-color: #ffffcc }
.highlight  { background: #f0f0f0; }
.highlight .c { color: #60a0b0; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #007020; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #60a0b0; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #60a0b0; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #007020 } /* Comment.Preproc */
.highlight .cpf { color: #60a0b0; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #60a0b0; font-style: italic } /* Comment.Single */
.highlight .cs { color: #60a0b0; background-color: #fff0f0 } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #c65d09; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #007020; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #007020; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #007020; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #007020 } /* Keyword.Pseudo */
.highlight .kr { color: #007020; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #902000 } /* Keyword.Type */
.highlight .m { color: #40a070 } /* Literal.Number */
.highlight .s { color: #4070a0 } /* Literal.String */
.highlight .na { color: #4070a0 } /* Name.Attribute */
.highlight .nb { color: #007020 } /* Name.Builtin */
.highlight .nc { color: #0e84b5; font-weight: bold } /* Name.Class */
.highlight .no { color: #60add5 } /* Name.Constant */
.highlight .nd { color: #555555; font-weight: bold } /* Name.Decorator */
.highlight .ni { color: #d55537; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #007020 } /* Name.Exception */
.highlight .nf { color: #06287e } /* Name.Function */
.highlight .nl { color: #002070; font-weight: bold } /* Name.Label */
.highlight .nn { color: #0e84b5; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #062873; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #bb60d5 } /* Name.Variable */
.highlight .ow { color: #007020; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #40a070 } /* Literal.Number.Bin */
.highlight .mf { color: #40a070 } /* Literal.Number.Float */
.highlight .mh { color: #40a070 } /* Literal.Number.Hex */
.highlight .mi { color: #40a070 } /* Literal.Number.Integer */
.highlight .mo { color: #40a070 } /* Literal.Number.Oct */
.highlight .sa { color: #4070a0 } /* Literal.String.Affix */
.highlight .sb { color: #4070a0 } /* Literal.String.Backtick */
.highlight .sc { color: #4070a0 } /* Literal.String.Char */
.highlight .dl { color: #4070a0 } /* Literal.String.Delimiter */
.highlight .sd { color: #4070a0; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #4070a0 } /* Literal.String.Double */
.highlight .se { color: #4070a0; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #4070a0 } /* Literal.String.Heredoc */
.highlight .si { color: #70a0d0; font-style: italic } /* Literal.String.Interpol */
.highlight .sx { color: #c65d09 } /* Literal.String.Other */
.highlight .sr { color: #235388 } /* Literal.String.Regex */
.highlight .s1 { color: #4070a0 } /* Literal.String.Single */
.highlight .ss { color: #517918 } /* Literal.String.Symbol */
.highlight .bp { color: #007020 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #06287e } /* Name.Function.Magic */
.highlight .vc { color: #bb60d5 } /* Name.Variable.Class */
.highlight .vg { color: #bb60d5 } /* Name.Variable.Global */
.highlight .vi { color: #bb60d5 } /* Name.Variable.Instance */
.highlight .vm { color: #bb60d5 } /* Name.Variable.Magic */
.highlight .il { color: #40a070 } /* Literal.Number.Integer.Long */</style>
<h1>iOS技术栈</h1>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<ul>
<li><p><a href="#%E7%BD%91%E7%BB%9C">网络</a></p></li>
<li><p><a href="#%E7%BD%91%E7%BB%9C">网络</a></p>

<ul>
<li><a href="#%E5%BC%B1%E7%BD%91%E7%BB%9C">弱网络</a></li>
<li><a href="#%E6%B5%81%E9%87%8F">流量</a></li>
</ul></li>
<li><p><a href="#%E5%86%85%E5%AD%98">内存</a></p></li>
<li><p><a href="#%E5%AD%98%E5%82%A8">存储</a></p></li>
<li><p><a href="#%E5%A4%9A%E7%BA%BF%E7%A8%8B">多线程</a></p></li>
<li><p><a href="#%E5%8A%A8%E7%94%BB">动画</a></p></li>
<li><p><a href="#%E7%BB%98%E5%9B%BE">绘图</a></p></li>
<li><p><a href="#%E5%93%8D%E5%BA%94%E5%BC%8F">响应式</a></p></li>
<li><p><a href="#%E7%A1%AC%E4%BB%B6">硬件</a></p></li>
<li><p><a href="#%E6%80%A7%E8%83%BD">性能</a></p></li>
<li><p><a href="#%E6%B5%8B%E8%AF%95">测试</a></p>

<ul>
<li><a href="#%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95">单元测试</a></li>
<li><a href="#ui%E6%B5%8B%E8%AF%95">UI测试</a></li>
</ul></li>
<li><p><a href="#web%E4%BA%A4%E4%BA%92">Web交互</a></p></li>
<li><p><a href="#%E8%B7%A8%E5%B9%B3%E5%8F%B0">跨平台</a></p>

<ul>
<li><a href="#react-native">React Native</a></li>
<li><a href="#flutter">Flutter</a></li>
</ul></li>
<li><p><a href="#runloop">Runloop</a></p></li>
<li><p><a href="#runtime">Runtime</a></p></li>
<li><p><a href="#%E7%AC%AC%E4%B8%89%E6%96%B9%E5%BA%93">第三方库</a></p></li>
<li><p><a href="#%E7%A7%81%E6%9C%89%E5%BA%93">私有库</a></p></li>
<li><p><a href="#%E7%AE%97%E6%B3%95">算法</a></p>

<ul>
<li><a href="#%E6%8E%92%E5%BA%8F">排序</a></li>
<li><a href="#%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F">快速排序</a></li>
<li><a href="#%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F">冒泡排序</a></li>
<li><a href="#%E9%80%89%E6%8B%A9%E6%8E%92%E5%BA%8F">选择排序</a></li>
</ul></li>
<li><p><a href="#%E5%85%AD%E5%A4%A7%E8%AE%BE%E8%AE%A1%E5%8E%9F%E5%88%99">六大设计原则</a></p>

<ul>
<li><a href="#solid%E5%8E%9F%E5%88%99">Solid原则</a></li>
<li><a href="#%E5%8D%95%E4%B8%80%E5%8A%9F%E8%83%BD%E5%8E%9F%E5%88%99">单一功能原则</a></li>
<li><a href="#%E5%BC%80%E9%97%AD%E5%8E%9F%E5%88%99">开闭原则</a></li>
<li><a href="#%E9%87%8C%E6%B0%8F%E6%9B%BF%E6%8D%A2%E5%8E%9F%E5%88%99">里氏替换原则</a></li>
<li><a href="#%E6%8E%A5%E5%8F%A3%E9%9A%94%E7%A6%BB%E5%8E%9F%E5%88%99">接口隔离原则</a></li>
<li><a href="#%E4%BE%9D%E8%B5%96%E5%8F%8D%E8%BD%AC%E5%8E%9F%E5%88%99">依赖反转原则</a></li>
<li><a href="#%E6%9C%80%E5%B0%91%E7%9F%A5%E8%AF%86%E5%8E%9F%E5%88%99">最少知识原则</a></li>
</ul></li>
<li><p><a href="#%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F">面向对象设计模式</a></p>

<ul>
<li><a href="#%E5%88%9B%E5%BB%BA%E5%9E%8B">创建型</a></li>
<li><a href="#%E7%BB%93%E6%9E%84%E5%9E%8B">结构型</a></li>
<li><a href="#%E8%A1%8C%E4%B8%BA%E5%9E%8B">行为型</a></li>
</ul></li>
<li><p><a href="#demo">demo</a></p>

<ul>
<li><a href="#%E5%BE%97%E5%91%97%E9%A6%96%E9%A1%B5">得呗首页</a></li>
</ul></li>
</ul>

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<h1>网络</h1>

<h2>弱网络</h2>

<h2>流量</h2>

<h1>内存</h1>

<h1>存储</h1>

<h1>多线程</h1>

<h1>动画</h1>

<h1>绘图</h1>

<h1>响应式</h1>

<h1>硬件</h1>

<h1>性能</h1>

<h1>测试</h1>

<h2>单元测试</h2>

<h2>UI测试</h2>

<h1>Web交互</h1>

<h1>跨平台</h1>

<h2>React Native</h2>

<h2>Flutter</h2>

<h1>Runloop</h1>

<h1>Runtime</h1>

<h1>第三方库</h1>

<h1>私有库</h1>

<h1>算法</h1>

<h2>排序</h2>

<h3>快速排序</h3>

<h3>冒泡排序</h3>

<h3>选择排序</h3>

<h1>六大设计原则</h1>

<h2>Solid原则</h2>

<p>是针对面向对象的程序设计提出的，即使在反思面向对象一些问题的现在，这一原则内的很多东西也有很重要的参考意义。</p>

<h2>单一功能原则</h2>

<p>不要考虑在模块内实现与它不相关的功能，比如在一个类中既要处理string MD5又要处理图片的解压缩，这就是明显的违反单一功能原则的例子。再往细说，其实在方法内也不应该处理过多的事情。</p>

<h2>开闭原则</h2>

<p>设计模块时要考虑对扩展开发对修改封闭，简单理解就是提炼不变的逻辑，将稳定的部分封装成模块的核心逻辑，对可扩展的部分进行注入。</p>

<h2>里氏替换原则</h2>

<p>指的是所有的子类都可以替换父类，但是一般情况下我们是不会通过子类去破坏父类的逻辑。</p>

<h2>接口隔离原则</h2>

<p>对于client应该隐藏不需要的细节，隔离这些部分不去依赖它们，使API的依赖更加简洁。</p>

<h2>依赖反转原则</h2>

<p>指的是高层次的模块不应依赖低层次的模块，个人认为这是个伪命题，因为高层次的模块一旦依赖低层次的模块，那它就不是高层次的模块了。如果高层次模块确实需要依赖某些东西的时候，所依赖的东西应该是抽象的。</p>

<h2>最少知识原则</h2>

<p>开发人员在使用模块的时候，对该模块知道的越少才越好。</p>

<h1>面向对象设计模式</h1>

<h2>创建型</h2>

<h2>结构型</h2>

<h2>行为型</h2>

<h1>demo</h1>

<h2>得呗首页</h2>

			          	</article>
			        </div>
					</div>
	      </body>
	    </html>
			<script type="text/javascript" src="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/js/jquery-1.4.4.min.js"></script>
			<script type="text/javascript" src="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/js/jquery.ztree.all-3.5.min.js"></script>
			<script type="text/javascript" src="/Library/Ruby/Gems/2.3.0/gems/tocmd-0.4.3/vendor/toc/js/ztree_toc.js"></script>
			<SCRIPT type="text/javascript" >
			<!--
			$(document).ready(function(){
				$('#tree').ztree_toc({
					is_auto_number:true,
					documment_selector:'.markdown-body'
				});
			});
			//-->
			</SCRIPT>
	  
