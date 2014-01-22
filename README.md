##Vertical Thumbnail Carousel
This repository use for add vertical thumbnail carosel while using Twitter Bootstrap V 3.0.3

##Browser Compatibility (Tested on)
>+ Internet Explorer 8.0 (No border Support)
Add Carousel items
>+ Internet Explorer 9.0

>+ .Internet Explorer 10.0

>+ Internet Explorer 11.0

>+ Windows Phone 7 - 8 IE 9 - 10

>+ Google Chrome Version 32.0.1700.76 m

>+ Firefox Version 26.0

## How To Invoke code in Action ?
##CSS Call
<pre><code>&lt;link href="css/bootstrap.css" rel="stylesheet" type="text/css"&gt;
&lt;link href="css/style.css" rel="stylesheet" type="text/css"&gt;
</code></pre>


Js Call
<pre><code>&lt;script src="js/jquery.min.js">&lt;/script> 
&lt;script src="js/bootstrap.js">&lt;/script> 
&lt;script src="js/script.js">&lt;/script></pre></code>

HTML Code
Add Navigation Icon

<pre><code>&lt;a class="left carousel-control" href="#myCarousel" data-slide="prev">&lt;img src="icon/up.png">&lt;/a>
&lt;a class="right carousel-control" href="#myCarousel" data-slide="next">&lt;img src="icon/down.png">&lt;/a></code></pre>


Add  Carousel items

<pre><code>&lt;div class="carousel-inner"&gt;
			
		&lt;div class="item active"&gt;
			&lt;div class="row-fluid"&gt;
			  &lt;table&gt;
			  &lt;tr&gt;
				&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/1.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
			  &lt;/tr&gt;
			  &lt;tr&gt;
				&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/2.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
			  &lt;/tr&gt;
			  &lt;tr&gt;
				&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/3.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
			  &lt;/tr&gt;
			  &lt;tr&gt;
				&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/4.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
			  &lt;/tr&gt;
			  &lt;/table&gt;
			&lt;/div&gt;&lt;!--/row-fluid--&gt;
		&lt;/div&gt;&lt;!--/item--&gt;
		 
		&lt;div class="item"&gt;
			&lt;div class="row-fluid"&gt;
			   &lt;table&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/5.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/6.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/7.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/8.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
			  &lt;/table&gt;
			&lt;/div&gt;&lt;!--/row-fluid--&gt;
		&lt;/div&gt;&lt;!--/item--&gt;
		 
		&lt;div class="item"&gt;
			&lt;div class="row-fluid"&gt;
				&lt;table&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/9.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/10.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/11.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				  &lt;tr&gt;
					&lt;td&gt;&lt;div class="span3"&gt;&lt;a href="#x" style = " width:50px; " class="thumbnail"&gt;&lt;img src="image/12.gif" alt="Image" style="max-width:100%; width:50px;"&gt;&lt;/a&gt;&lt;/div&gt;&lt;/td&gt;
				  &lt;/tr&gt;
				&lt;/table&gt;
			&lt;/div&gt;&lt;!--/row-fluid--&gt;
		&lt;/div&gt;&lt;!--/item--&gt;
     
    &lt;/div&gt;</code></pre>
<h2>Contributing</h2>
<hr>
<br>
1 Fork it.
<br>
2 Open a Pull Request
<br>

<br><h2>License</h2><hr><br>

Some the css were written by Bootstrap and therefore fall under their license. All other source code is released under the MIT License.

<h2>Support</h2>
<hr>
<pre>
For any query and development help. mail me at contact@tutorialdrive.org
</pre>

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/tutorialdrive/bootstrap-vertical-thumbnail-carousel/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
