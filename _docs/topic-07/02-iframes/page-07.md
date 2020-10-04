---
title: Maps in the Iframe Element
module: topic-07
permalink: /topic-07/iframe-element-maps/
---

<div class="divider-heading"></div>

In addition to displaying other webpages in the main webpage, the iframe element is often used to display specific types of instances, like including a [Google Map](https://www.google.com/maps) of the University of Montana.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<iframe src="https://www.google.com/maps/place/University+of+Montana/@46.8600672,-113.9873968,17z/data=!3m1!4b1!4m5!3m4!1s0x535dcc33f19815cb:0x9c296b8546ca9abf!8m2!3d46.8600672!4d-113.9852081" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```


<div class="external-embed" style="width: 600px; margin: auto;">
  <iframe src="https://www.google.com/maps/place/University+of+Montana/@46.8600672,-113.9873968,17z/data=!3m1!4b1!4m5!3m4!1s0x535dcc33f19815cb:0x9c296b8546ca9abf!8m2!3d46.8600672!4d-113.9852081" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>


<div class="divider-pg"></div>


## How-To:
From the Google maps page, after completing a search, you can click the “share” button. This opens a separate pop-up, where you should select the “Embed a map ”option. You can then tweak the display options, and copy Google's iframe code to include on your site.


<img src="../img/embed-google-maps.gif" title="Google Map embed" alt="Image showing the “embed map” option from google maps" width="600" />


Including this code on your site will create an embedded Google Map that your visiting users may interact with. Typically, this is useful in showing where a business location is.
