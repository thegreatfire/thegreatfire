---
<!-- layout: post -->
title: BOOK US
description: 'Book now for 2021'
image: assets/images/amp.JPG
<!-- image: assets/images/pic07.jpg -->
show_tile: true
nav-menu: false
---

<!-- Details -->
<section id="intro" class="spotlights" style="margin-top:2em;">
	<div class="inner">
		<h2 style="text-transform: uppercase;">Book The Great Fire</h2>
		<p>Have you been searching for a "cover band near me"? We are available for public and private functions. From live music venues and festivals to parties, corporate events and weddings in London, Kent, Sussex and Surrey, and all over the UK.</p>
	</div>
</section>

<!-- Contact -->
<section id="contact">
	<div class="inner">
		<section>
			<h2 style="text-transform: uppercase;">Booking Enquiry</h2>
			<p>Contact us for your wedding, party or event across the whole of Sussex, Kent, Surrey & London - or even further afield.</p> 
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
		<section class="split">
			<section>
				<div class="contact-method">
					<span class="icon alt fa-envelope"></span>
					<h3>Email</h3>
					<a href="">{{ site.email }}</a>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-instagram"></span>
					<h3>Instagram</h3>
					<a href="{{ site.instagram_url }}">@greatfireband</a>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-facebook"></span>
					<h3>Facebook</h3>
					<a href="{{ site.facebook_url }}">@greatfireband</a>
				</div>
			</section>
		</section>
	</div>
</section>