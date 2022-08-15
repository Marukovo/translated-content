---
title: animation-duration
slug: Web/CSS/animation-duration
tags:
  - CSS
  - CSS Animations
  - CSS Property
  - Experimental
  - Reference
translation_of: Web/CSS/animation-duration
---
<div>{{ CSSRef() }}{{ SeeCompatTable() }}</div>

<h2 id="概述">概述</h2>

<p><code>animation-duration</code>属性指定一个动画周期的时长。</p>

<p>默认值为 0s，表示无动画。</p>

<p>使用简写属性{{cssxref("animation")}}很方便地同时设置所有的动画属性。</p>

<p>{{cssinfo}}</p>

<h2 id="语法">语法</h2>

<pre class="twopartsyntaxbox notranslate"><a href="/en-US/docs/CSS/Value_definition_syntax">Formal syntax</a>: {{csssyntax("animation-duration")}}
</pre>

<pre class="notranslate">animation-duration: 6s
animation-duration: 120ms
animation-duration: 1s, 15s
animation-duration: 10s, 30s, 230ms
</pre>

<h3 id="值">值</h3>

<dl>
 <dt><code>&lt;time&gt;</code></dt>
 <dd>一个动画周期的时长，单位为秒 (s) 或者毫秒 (ms)，无单位值无效。</dd>
</dl>

<div class="note">
 <p><strong>备注：</strong>负值无效，浏览器会忽略该声明，但是一些早期的带前缀的声明会将负值当作 0s。</p>
</div>

<h2 id="示例">示例</h2>

<p>See <a href="/en/CSS/CSS_animations">CSS animations</a> for examples.</p>

<h2 id="Specifications">规范</h2>

{{Specifications}}

<h2 id="Browser_Compatibility">浏览器兼容</h2>

{{Compat("css.properties.animation-duration")}}

<h2 id="See_also">See also</h2>

<ul>
 <li><a href="/en-US/docs/CSS/Tutorials/Using_CSS_animations">Using CSS animations</a></li>
 <li>{{ domxref("AnimationEvent", "AnimationEvent") }}</li>
</ul>