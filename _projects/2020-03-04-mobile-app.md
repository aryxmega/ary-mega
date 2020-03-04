---
title: Mobile App
subtitle: Monobrand offers an exclusive range of unique switch programs, carefully selected lighting, a fabulous array of door & furniture hardware.
date: 2020-03-04 00:00:00
description: Monobrand offers an exclusive range of unique switch programs, carefully selected lighting, a fabulous array of door & furniture hardware.
featured_image: '/mobile-app/mobile-app-01.png'
accent_color: '#BED7D4'
gallery_images:
  - /mobile-app/mobile-app-01.png
  - /mobile-app/mobile-app-02.png
---

Supes Simps Grid Sys (aka SSGS) is a a super simple grid system I whipped up that's mad easy to customize to fit your millennial needs. It currently supports Chrome, Firefox, Safari, Opera, IE and major mobile devices.
{: .lead}

#### Installation is supes eaze:

-   Clone: [https://github.com/awwwry/supes-simps-grids-sys.git](https://github.com/awwwry/supes-simps-grids-sys.git)
-   Download latest .zip file: [https://github.com/awwwry/supes-simps-grids-sys/archive/master.zip](https://github.com/awwwry/supes-simps-grids-sys/archive/master.zip)


#### Link-up the stylesheet in your <head>

```html
<link rel="stylesheet" type="text/css" href="style/sheet.css">
```

#### Structurin' your layouts real nasty.
```html
<div class="wrap">
    <div class="block-3">Content here</div>
    <div class="block-3">Content here</div>
    <div class="block-3">Content here</div>
</div>
```
Creating a three-column layout, for example, is supes simps. Wrap the `.block`'s in a `.wrap` class to clear the left floats.

**Note:** this will scale each column down to 100% width on mobile.

#### Gettin' fluid widdit.
Maybe you want to kick-it old school and create a two-column layout based on percentage. It's mad simps. As long as the `.block-` classes equal 100%, shit'll will be fire 🔥
```html
<div class="wrap">
    <div class="block-75">Some rad content here</div>
    <div class="block-25">Some informational content here</div>
</div>
```

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/projects/mobile-app/mobile-app-01.png,/images/projects/mobile-app/mobile-app-02.png
	"
%}

#### That's it.

If you have any questions, don't hesitate to holler at <a href="https://media.giphy.com/media/Yq9Qvg8yqfiQtWP6gn/giphy.gif" title="Really bruh" target="_blank">no-reply@gmail.com</a>.