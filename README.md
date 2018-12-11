# txtscroll.js

txtscroll.js是一个基于jQuery的文本无缝循环滚动插件，使用插件之前需要引入jQuery。


<h3>特性</h3>
支持jQuery3.3+ <br />
支持移动端 <br />
支持响应式 <br />
支持鼠标悬浮停止

<h3>参数</h3>
<div class="txt">
	<table width="100%" cellpadding="0" cellspacing="0">
		<tr>
			<th class="td1">参数</th>
			<th class="td2">默认值</th>
			<th class="td3">说明</th>
		</tr>
		<tr>
			<td class="td1">speed</td>
			<td class="td2">50</td>
			<td class="td3">
				滚动间隔时间，每次滚动距离为1px
			</td>
		</tr>
	</table>
</div>


<h3>使用方法</h3>
<div class="txt">
<pre>
&lt;div class="txt-scroll"&gt;
    &lt;div class="scrollbox"&gt;
        &lt;div class="txt"&gt;
           深圳市移联天下电子商务有限公司成立于2014年， 是集移动互联网新消费模式、品质消费体验、社交分享于一体的会员权益服务平台。基于移动互联网消费升级新需求，连接线上线下消费新场景，通过大数据、人工智能及云计算等技术手段，致力于为用户连接优质服务、快乐分享、成就美好生活。
        &lt;/div&gt;
    &lt;/div&gt;
&lt;/div&gt;


&lt;script src="js/jquery-3.3.1.min.js"&gt;&lt;/script&gt;

&lt;script src="js/txtscroll.js"&gt;&lt;/script&gt;
&lt;script&gt;
  $('.txt-scroll').txtscroll({
	'speed': 50
  });
&lt;/script&gt;
</pre>
