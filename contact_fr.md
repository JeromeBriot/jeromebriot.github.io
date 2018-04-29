---
layout: page
title: Comment puis-je vous aider ?
permalink: /fr/contact/
nav_title: Contact
ref: contact
lang: fr
---

<form class="wj-contact" action="https://formspree.io/{{site.email}}" method="POST">
	<input type="text" name="name" placeholder="Nom">
	<input type="text" name="email" placeholder="Adresse email">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="//{{ site.url | remove: "https://"}}/fr/merci/">
    <input type="hidden" name="_subject" value="Nouvelle soumission de formulaire de contact">
	<input type="hidden" name="_language" value="fr" />
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Envoyer">
</form>