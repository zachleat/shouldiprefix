---
title: box-sizing
url: box-sizing
prefixed: true
---

<article id="box-sizing" class="feature prefix-{{page.prefixed}}">
	<header class="feature__header">
		<h2>box-sizing</h2>
	</header>
	<p class="feature__description">
		Method of specifying whether or not an element's borders and padding should be included in size units
	</p>
<pre class="feature__code"><code>
	.example {
	  -webkit-box-sizing: border-box;
	     -moz-box-sizing: border-box;
	          box-sizing: border-box;
	}
</code></pre>
	<footer class="feature__footer">
		<a href="http://caniuse.com/box-sizing">Browser support</a> 
		<a href="http://html5please.com/#box-sizing">Usage advice</a> 
		<a href="https://github.com/davidhund/shouldiprefix/blob/ghpages/_posts/{{page.title}}.md">Edit this</a> 
		<span class="feature__prefix">{{page.prefixed}}</span>
	</footer>
</article>