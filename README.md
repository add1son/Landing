# Landing
Building an HTML based landing page with a template as well as a javascript free redirect if noscript is running
# How Noscript works
```
<noscript>
  <style>html{display:none;}</style>
  <meta http-equiv="refresh" content="0.0;url=./index_nojs.html">
	<!-- Redirects to index_nojs.html should js be disabled -->
</noscript>
```
Change ./index_nojs.html to a javascript free version of landing
