---
title: ':optional'
slug: 'Web/CSS/:optional'
translation_of: 'Web/CSS/:optional'
---
<p>{{ CSSRef() }}</p>

<h2 id="摘要">摘要</h2>

<p><code>:optional</code> CSS <a href="/zh-CN/CSS/Pseudo-classes">伪类</a> 表示任意没有{{ htmlattrxref("required","input") }}属性的 {{ HTMLElement("input") }}，{{HTMLElement("select")}} 或  {{ HTMLElement("textarea") }} 元素使用它。</p>

<pre><code>/* Selects any optional &lt;input&gt; */
input:optional {
  border: 1px dashed black;
}</code>
</pre>

<p>它允许表单容易的展示可选字段并且渲染其外观。</p>

<div class="note">
<p>注：为必填字段设置外观，请使用 {{ cssxref(":required") }}伪类。</p>
</div>

<h2 id="语法">语法</h2>

{{csssyntax}}

<h2 id="例子">例子</h2>

<p>查看{{ cssxref(":invalid") }} 示例。</p>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

{{Compat("css.selectors.optional")}}

<h2 id="参见">参见</h2>

<ul>
 <li>{{ cssxref(":required") }}</li>
 <li>{{ cssxref(":invalid") }}</li>
 <li>{{ cssxref(":valid") }}</li>
 <li><a href="/zh-CN/docs/Learn/HTML/Forms/Form_validation">Form data validation</a></li>
</ul>