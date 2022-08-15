---
title: font-style
slug: Web/CSS/@font-face/font-style
translation_of: Web/CSS/@font-face/font-style
---
<p>{{CSSRef}}</p>

<h2 id="概述">概述</h2>

<p><strong>font-style</strong> 描述符允许开发者在 @font-rule 规则中为指定字体样式 (该条目区别于 font-style，意指用在 @font-rule 中的 font-style 属性)</p>

<p>For a particular font family, authors can download various font faces which correspond to the different styles of the same font family, and then use the <code>font-style </code>descriptor to explicitly specify the font face's style. The values for the CSS descriptor is same as that of its corresponding font property.</p>

<p>{{cssinfo}}</p>

<h2 id="Syntax">Syntax</h2>

<pre class="brush: css">font-style: normal;
font-style: italic;
font-style: oblique;</pre>

<h3 id="Values">Values</h3>

<p><code><strong>normal</strong></code><br>
 Selects the normal version of the font-family.</p>

<p><strong><code>italic</code></strong><br>
 Specifies that font-face is an italicized version of the normal font .</p>

<p><strong><code>oblique</code></strong><br>
 Specifies that the font-face is an artificially sloped version of the normal font.</p>

<h3 id="Formal_syntax">Formal syntax</h3>

{{csssyntax}}

<h2 id="Examples">Examples</h2>

<p>As an example, consider the garamond font family, in its normal form, we get the following result:</p>

<pre class="brush: css">@font-face {
  font-family: garamond;
  src: url('garamond.ttf');
}</pre>

<p><img alt="unstyled Garamond" src="garamondunstyled.jpg"></p>

<p>The italicized version of this text uses the same glyphs present in the unstyled version, but they are artificially sloped by a few degrees.</p>

<p><img alt="artificially sloped garamond" src="garamondartificialstyle.jpg"></p>

<p>On the other hand, if a true italicized version of the font family exists, we can include it in the <code>src </code>descriptor and specify the font style as italic, so that it is clear that the font is italicized. True italics use different glyphs and are a bit different from their upright counterparts, having some unique features and generally have a rounded and calligraphic quality. These fonts are specially created by font designers and are <strong>not</strong> artificially sloped.</p>

<pre class="brush: css">@font-face {
  font-family: garamond;
  src: url('garamond-italic.ttf');
  font-style: italic;
}</pre>

<p><img alt="italic garamond" src="garamonditalic.jpg"></p>

<h2 id="Specifications">Specifications</h2>

{{Specifications}}

<h2 id="Browser_compatibility">Browser compatibility</h2>

{{Compat("css.at-rules.font-face.font-style")}}