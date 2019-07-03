# dragula
<div class="alert cjms" role="alert">插件描述：dragula让你能够很方便地实现拖拽功能的JS库。</div>
<p>Dragula 是一个 JavaScript 库，实现了网页上的拖放功能。提供 JavaScript、AngularJS 和 React 版本。</p><h4>特性</h4><ul class=" list-paddingleft-2" style="list-style-type: disc;"><li><p>超级易于使用</p></li><li><p>没有臃肿的依赖</p></li><li><p>计算出自身的排序顺序</p></li><li><p>阴影将放置该项目提供可视反馈</p></li><li><p>触摸事件！</p></li></ul><p>示例代码：</p><pre class="brush:js;toolbar:false">dragula([left,&nbsp;right]).on(&#39;drag&#39;,&nbsp;function&nbsp;(el)&nbsp;{
&nbsp;&nbsp;el.className&nbsp;=&nbsp;el.className.replace(&#39;&nbsp;animazing&#39;,&nbsp;&#39;&#39;);
}).on(&#39;drop&#39;,&nbsp;function&nbsp;(el)&nbsp;{
&nbsp;&nbsp;setTimeout(function&nbsp;()&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;el.className&nbsp;+=&nbsp;&#39;&nbsp;animazing&#39;;
&nbsp;&nbsp;},&nbsp;0);
});</pre><p><br /></p>
