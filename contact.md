---
layout: page
title: How can I help you?
permalink: /contact/
nav_title: Contact
ref: contact
lang: en
---

<!--- https://gist.github.com/sharu725/b8bc09d8a6bb57c637df0b5ae958c155 --->

<form class="wj-contact" action="https://formspree.io/{{site.email}}" method="POST">
	<input type="text" name="name" placeholder="Name">
    <input type="text" name="email" placeholder="Email Address">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="//{{ site.url | remove: "https://"}}/thanks/">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
	<input type="hidden" name="_language" value="en" />
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>