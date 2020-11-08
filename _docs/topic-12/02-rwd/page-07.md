---
title: Responsive Images
module: topic-12
permalink: /topic-12/rwd-images/
categories: development
tags:
---

<div class="divider-heading"></div>

## Responsive Images

### width property

If the width property is set to a percentage and the height is set to "auto", the image will be responsive and scale up and down.

```css

img {
  width: 100%;
  height: auto;
}

```

**Note** the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.

### max-width property

If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size.

```css

img {
  max-width: 100%;
  height: auto;
}

```

Experiment with `width` and `max-width`

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="JjKazJq" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Media Queries" class="codepen"></p>
</div>





<a href="https://www.w3schools.com/css/css_rwd_images.asp" target="_new"><em>Reference</em></a>