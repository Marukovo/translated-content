---
title: <length-percentage>
slug: Web/CSS/length-percentage
translation_of: Web/CSS/length-percentage
---
<div>{{CSSRef}}</div>

<p>The <strong><code>&lt;length-percentage&gt;</code></strong> <a href="/en-US/docs/Web/CSS">CSS</a> <a href="/en-US/docs/Web/CSS/CSS_Types">data type</a> represents a value that can be either a {{Cssxref("length")}} or a {{Cssxref("percentage")}}.<br>
 The <strong><code>&lt;length-percentage&gt; </code></strong>CSS 数据类型表示一个值，该值可以是&lt;length&gt;或&lt;percentage&gt;。</p>

<h2 id="Syntax">Syntax</h2>

<p>Refer to the documentation for {{Cssxref("length")}} and {{Cssxref("percentage")}} for details of the individual syntaxes allowed by this type.</p>

<h2 id="Use_in_calc()">Use in <code>calc()</code></h2>

<p>Where a <code>&lt;length-percentage&gt;</code> is specified as an allowable type, this means that the percentage resolves to a length and therefore can be used in a {{cssxref("calc", "calc()")}} expression. Therefore, all of the following values are acceptable for {{cssxref("width")}}:</p>

<pre class="brush: css example-good">width: 200px;
width: 20%;
width: calc(100% - 200px);
</pre>

<h2 id="Specifications">Specifications</h2>

{{Specifications}}

<h2 id="Browser_compatibility">Browser compatibility</h2>



<p>{{Compat("css.types.length-percentage")}}</p>