# Carouser

Plugin for creating carousel width autoplay

For using just add <code>&lt;script src="js/slider.min.js">&lt;/script></code> to the body

Markup example:
<pre>
	&lt;div class="slider" id="slider">
		&lt;div class="slItems">
			&lt;div class="slItem" style="background-image: url('img/1.jpg');">
				&lt;div class="slText">
					Lorem ipsum dolor sit amet, consectetur adipiscing elit.
				&lt;/div>
			&lt;/div>
			&lt;div class="slItem" style="background-image: url('img/2.jpg');">
				&lt;div class="slText">
					Praesent consequat sapien ut dui hendrerit imperdiet.  
				&lt;/div>
			&lt;/div>
			&lt;div class="slItem" style="background-image: url('img/3.jpg');">
				&lt;div class="slText">
					Morbi aliquam tristique rutrum. 
				&lt;/div>
			&lt;/div>
		&lt;/div>
	&lt;/div>
</pre>

Init example:
<pre>
  $('#slider').rbtSlider({
		height: '100vh', 
		'dots': true,
		'arrows': true,
		'auto': 3
	});
</pre>
