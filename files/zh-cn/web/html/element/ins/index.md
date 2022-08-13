---
title: <ins>
slug: Web/HTML/Element/ins
tags:
  - Element
  - HTML
  - HTML edits
  - Reference
  - Web
translation_of: Web/HTML/Element/ins
---
<h2 id="简介">简介</h2>

<p>{{HTMLRef}}<br>
 <strong>HTML <code>&lt;ins&gt;</code> 元素</strong>定义已经被插入文档中的文本。</p>

<p>{{EmbedInteractiveExample("pages/tabbed/ins.html", "tabbed-standard")}}</p>

<ul>
 <li><dfn><a href="/en-US/docs/HTML/Content_categories">内容</a>分类</dfn><a href="/zh-CN/docs/Web/Guide/HTML/Content_categories#短语元素（Phrasing_content）">短语元素</a> 或者 <a href="/zh-CN/docs/Web/Guide/HTML/Content_categories#流式元素（Flow_content）">流式元素</a> 。</li>
 <li><dfn>允许内容</dfn> <a href="/zh-CN/docs/Web/Guide/HTML/Content_categories#透明内容模型（Transparent_content_model）">透明内容模型</a>。</li>
 <li><dfn>标签闭合</dfn> {{no_tag_omission}}</li>
 <li><dfn>允许的父级标签</dfn>任意<a href="/zh-CN/docs/Web/Guide/HTML/Content_categories#短语元素（Phrasing_content）">短语元素</a></li>
 <li><dfn>允许的 ARIA 角色</dfn>任意</li>
 <li><dfn>DOM 接口</dfn> {{domxref("HTMLModElement")}}</li>
</ul>

<h2 id="属性">属性</h2>

<p>该元素支持所有 <a href="https://developer.mozilla.org/en-US/docs/HTML/Global_attributes">全局特性</a>，除此以外还支持下列属性：</p>

<dl>
 <dt>{{htmlattrdef("cite")}}</dt>
 <dd>cite 属性的值指向一个文档的 URL，该文档解释了文本被插入或修改的原因。（目前该属性还没有被主流浏览器支持）</dd>
 <dt>{{htmlattrdef("datetime")}}</dt>
 <dd>该特性指示的此修改发生的时间和日期，并且该特性的值必须是<a href="http://www.w3.org/TR/2011/WD-html5-20110525/common-microsyntaxes.html#valid-date-string-with-optional-time">一个有效的日期或者时间字符串</a>。如果该值不能被解析为日期或者时间，则该元素不具有相关联的时间标记。</dd>
</dl>

<h2 id="示例">示例</h2>

<pre class="brush: html">&lt;ins&gt;这一段文本是新插入至文档的。&lt;/ins&gt;</pre>

<h3 id="结果">结果</h3>

<p>这一段文本是新插入至文档的。</p>

<h2 id="Specifications">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

<p>{{Compat}}</p>

<h2 id="参阅">参阅</h2>

<ul>
 <li>{{HTMLElement("del")}}</li>
</ul>