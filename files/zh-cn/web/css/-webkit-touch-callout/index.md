---
title: '-webkit-touch-callout'
slug: Web/CSS/-webkit-touch-callout
translation_of: Web/CSS/-webkit-touch-callout
---
<p>{{CSSRef}} {{Non-standard_header}}</p>

<h2 id="概述">概述</h2>

<p><code>-webkit-touch-callout</code> 这个<a href="/en-US/docs/Web/CSS">CSS</a> 属性禁用了默认的 callout 展示， callout 是指当触摸并按住一个元素的时候出现的提示。<br>
 <br>
 当在 iOS 上一直按住一个目标元素时，Safari 会展示一个关于这个链接的 callout 信息。<code>webkit-touch-callout</code>属性允许禁用掉这一行为。</p>

<h2 id="Syntax">语法</h2>

<pre class="twopartsyntaxbox"><a href="/en-US/docs/Web/CSS/CSS_values_syntax">Formal syntax</a>: default | none
</pre>

<pre><code class="language-html">-webkit-touch-callout: default</code>   /* displays the callout */
<code class="language-html">-webkit-touch-callout: none</code>      /* disables the callout */

<code class="language-html">-webkit-touch-callout</code>: initial
-webkit-touch-callout: inherit
-webkit-touch-callout: unset</pre>

<h3 id="可能的值">可能的值</h3>

<dl>
 <dt><code>default</code></dt>
 <dd>此值表示显示默认的 callout</dd>
 <dt><code>none</code></dt>
 <dd>此值表示禁用 callout</dd>
</dl>

<h2 id="示例">示例</h2>

<pre class="brush: css">.example {
  -webkit-touch-callout: none;
}
</pre>

<h2 id="Browser_Compatibility">浏览器兼容性</h2>

{{Compat("css.properties.-webkit-touch-callout")}}