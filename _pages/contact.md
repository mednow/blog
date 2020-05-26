---
layout: contact-page
title: Contact
permalink: /contact
comments: false
---

<form id="my-form" action="https://formspree.io/xbjzgodz" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<button id="my-form-button" class="btn btn-dark" type="submit">Send</button>
</form>
<br>
<p id="my-form-status"></p>