---
title: E-mail Links
module: topic-05
permalink: /topic-05/email-links/
categories: html
tags: elements, email, link
---

<div class="divider-heading"></div>

A very common type of hyperlinking is to create an **e-mail link** within a page. This is accomplished by prepending “`mailto:`” to the desired e-mail address.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<a href="malto:user@example.com">User's E-mail</a>
```


So, to create a hyperlink that e-mails me:


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="JjXmbwb" data-default-tab="html,result" data-user="michaelcassens" data-embed-version="2" data-pen-title="[Intro-Web-Dev] Topic-05: Links Pt. 4" class="codepen"></p>
</div>


<span class="label label-info">Note</span> Clicking on such a link in a webpage will cause the webpage to try and open the user's default e-mail application. For that reason, it is also good practice to write the full e-mail address out. That way a user can easily copy the address from the browser into the e-mail client of their choice.
