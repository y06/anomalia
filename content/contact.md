---
title: "contact us"
description: "Contact informations and contact form"
repo: "#" # delete this line if you want blog-like posts for projects
weight: 0
draft: false
---

<ul class="au-list" style="text-align: center;">
<li>+421 948 151 589</li>
<li><a href="mailto:hello@anomalia.sk">hello@anomalia.sk</a></li>
</ul>

<ul class="contact-icons">
<a href="#"><li><i class="fa fa-instagram"></i></li></a>
<a href="#"><li><i class="fa fa-facebook"></i></li></a>
</ul>

<div class="contactform">
<form name="contact" method="POST" action="/thanks/" netlify>
<p>
	<input type="text" name="name" placeholder="Name:" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Your Name:'" required/>
</p>
<p>
	<input type="email" name="email" placeholder="E-mail:" onfocus="this.placeholder = ''" onblur="this.placeholder = 'E-mail:'" required/>
</p>
<p>
	<textarea name="message" placeholder="Message:" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Message:'" required></textarea>
	<button type="submit">send<i class="fa fa-paper-plane"></i></button>
</p>
</form>
</div>