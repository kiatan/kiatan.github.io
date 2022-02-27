---
layout: page
title: pages.contact
permalink: /contact
comments: false
---

<form action="https://formspree.io/f/mdobavlp" method="POST">    
<p class="mb-4">{% t contact.description %}</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="{% t contact.name %}*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="replyto" placeholder="{% t contact.email %}*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="{% t contact.message %}*" required></textarea>    
<input class="btn btn-dark" type="submit" value="{% t contact.send %}">
</form>