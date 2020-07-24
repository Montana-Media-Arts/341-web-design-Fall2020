---
title: Adding Attributes
module: topic-05
permalink: /topic-05/attributes/
categories: html
tags: attribute, paragraphs, tags
---

<div class="divider-heading"></div>

**Attributes** provide additional information about an HTML element. This may include information such as languages (US-English vs. French), URL links for text, the size to display a picture, or ways of identifying specific elements.

Attributes are always placed inside the opening tag for the element they refer to. Attributes are always provided in a **key=“value”** pair. The **key** is an identifier the the browser processor will recognize. These keys are defined by the W3 Consortium that defined HTML5 specification. The **value** provides information about the attribute.

The value is always surrounded by double quotations. One reason for this is that it allows for spaces to be used within the value for an attribute. Furthermore, the attribute will have one space placed between the tag label and the attribute, as well as between any subsequent attributes.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p align="left">This is a paragraph element, made with "<p>" tags.
<br/>
It will align to the left of its container.</p>
```
