---
title: Links to Other Sites
module: topic-05
permalink: /topic-05/links-to-others/
categories: html
tags: absolute, elements, link, url
---

<div class="divider-heading"></div>

Links that include the “<code>http/https</code>” as part of the entire URL are known as <b>absolute URLs</b>.</p>

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<a href="https://example.com" target="_blank">Link to Example.com</a>
```


Notice in the above link that it includes “`https`”. The “`https`” is required to signify to the browser that this is an ‘external’ link outside of the current document’s directory/server. **You must include either “`http`” or “`https`”.**

<span class="label label-success">Neat-O</span> The former is a older, established, version of the “hypertext transfer protocol”, which specified how data was sent between clients. The latter, is a “secure” version of this protocol. Whenever possible, you should provide “`https`” links (just check that they work first), as it provides a safer browsing experience.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="zEwMLb" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="External HTML Links" class="codepen"></p>
</div>
