---
layout: page
header:
  image_fullwidth: header-server-farm.jpg
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


<p class="hero">
Commit DB is designed from the ground up for the <strong>MySQL developers and DBAs</strong>. Connect to your servers on the road to develop new code or to check your data.  
</p>

<br>


<p class="text-center">
	<a href="https://itunes.apple.com/app/apple-store/id1128425956?pt=485856&ct=Site%20commit%20db&mt=8">
		<img src="{{ site.urlimg }}app-store-download.svg" class="app-store-badge">
	</a>
</p>


<div class="carousel">
  <div><img src="{{ site.urlimg }}screenshots/iPad - Screenshot 1.png" alt="slide 1" /></div>
  <div><img src="{{ site.urlimg }}screenshots/iPad - Screenshot 2.png" alt="slide 2" /></div>
  <div><img src="{{ site.urlimg }}screenshots/iPad - Screenshot 3.png" alt="slide 3" /></div>
  <div><img src="{{ site.urlimg }}screenshots/iPad - Screenshot 4.png" alt="slide 4" /></div>
  <div><img src="{{ site.urlimg }}screenshots/iPad - Screenshot 5.png" alt="slide 5" /></div>
  <div><img src="{{ site.urlimg }}screenshots/iPad - screenshot 6.png" alt="slide 6" /></div>
</div>


<script type="text/javascript">
	
	$('.carousel').slick({
		adaptiveHeight: true,
		autoplay: true,
		dots: true,
		fade: true,
  		cssEase: 'linear'
	});

</script>


<h2>Features</h2>

<br>

<ul class="fa-ul">
	<li>
		<i class="fa fa-code fa-li fa-4x" aria-hidden="true" style="color:blue"></i>
		<ul class="square">
			<li class="feature"><strong>Powerful SQL prompt</strong> / editor to write your code and execute your queries</li>
			<li class="feature">SQL syntax highlighting</li>
			<li class="feature">Local objects name highlighting in queries</li>
		</ul>
		<hr>
	</li>
	<li>
		<i class="fa fa-braille fa-li fa-4x" aria-hidden="true" style="color:green"></i>
		<ul class="square">
			<li class="feature"><strong>Optimized for iPad multitasking</strong></li>
			<li class="feature">Keyboard shortcuts for easier usage with a hardware keyboard</li>
			<li class="feature">Main SQL keywords directly available from the keyboard</li>
		</ul>
		<hr>
	</li>
	<li>
		<i class="fa fa-exchange fa-li fa-4x" aria-hidden="true" style="color:orange"></i>
		<ul class="square">
			<li class="feature"><strong>Synchronize your connections</strong> between devices with iCloud</li>
			<li class="feature">Import files from any iOS document provider extension (Dropbox, One Drive, Google Drive …)</li>
			<li class="feature">Export your queries to any iOS document provider extension</li>
			<li class="feature">Export the results of your queries to either CSV or JSON</li>
		</ul>
		<hr>
	</li>
	<li>
		<i class="fa fa-lock fa-li fa-4x" aria-hidden="true" style="color:red"></i>
		<ul class="square">
			<li class="feature">Connect to your databases directly or through a SSH tunnel</li>
			<li class="feature">SSH connection authenticated either by password or RSA key</li>
			<li class="feature">Secure your connections with SSL</li>
			<li class="feature">Protect access to the app with TouchID</li>
			<li class="feature">Make your connection read-only to avoid mistakes</li>
		</ul>
		<hr>
	</li>
	<li class="feature">
		<i class="fa fa-cubes fa-li fa-3x" aria-hidden="true" style="color:blueviolet"></i>
		<ul class="square">
			<li class="feature">Easily search for objects (table, view, field, constraint …) and paste their name in queries with one tap</li>
			<li class="feature">Browse all the objects in your db and see their definition / data / script ... with one tap</li>
			<li class="feature">Edit existing rows and insert new ones</li>
			<li class="feature">Easily start transactions and commit or rollback your modifications</li>
			<li class="feature">Sort your queries results with a tap on the columns headers</li>
			<li class="feature">Easily find the indexes, constraints, triggers and grants of a table</li>
		</ul>
		<hr>
	</li>
</ul>

