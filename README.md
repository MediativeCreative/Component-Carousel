## Component Carousel page

**See the preview component [here](https://mediativecreative.github.io/Component-Carousel/)**

### Code to edit

First you need to your javascript and CSS to make this component work.
Place this in the cartridge you want to create your carousel
```html
<script src="http://mediative.co/creativeservices/WM_CodeLibrary/component-carousel/JS/slick.js" type="text/javascript" charset="utf-8">
</script>
<link rel="stylesheet" type="text/css" href="http://mediative.co/creativeservices/WM_CodeLibrary/component-carousel/CSS/slick-theme.css">
```

You can copy paste this HTML section

```html
  <section class="lazy slider" data-sizes="100vw"">
    <div>
	<!--Type your code here-->
    </div>
    <div>
	<!--Type your code here-->
    </div>
    ...
  </section>
```
You can have as many `div` as you want. Each `div` will an item in you carousel.

Then just put the `Javascript` code at the bottom of your cartridge
```javascript
<script>
	$(document).on('ready', function() {
		$('.slider').on('init', function () {
			$('.slider').css({
				height: 'auto',
				visibility: 'visible'
			});
		});
	});
</script>
```
