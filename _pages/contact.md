---
title: "Ta kontakt!"
permalink: "/kontakt.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Send meg gjerne en melding og jeg vil ta kontakt så snart som mulig!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Navn*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-postadresse*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Skriv en melding*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>