---
title: 'Contacto'
intro_image: images/tree.png
---

Aquí va el formulario y los datos de contacto.

<form name='contact' method='post' data-netlify-recaptcha='true' action='/thank-you'><input type='hidden' name='form-name' value='contact' /><div class=form-group><label>Name</label>
<input type=text class=form-control name=Name placeholder="Enter your name" aria-label=Name required></div><div class=form-group><label>Contact #</label>
<input type=tel class=form-control name="Contact #" placeholder="your 10 digit mobile no." aria-label=contact_no minlength=10 maxlength=10 autocomplete=off required></div><div class=form-group><label>Email</label>
<input type=email class=form-control name="Email id" placeholder=abc@somemail.com aria-label=e_mail_address autocomplete=off required></div><div class=form-group><label>Message</label>
<textarea class=form-control name=Message placeholder="Enter your message" rows=2 aria-label=message spellcheck=false required></textarea></div><div class='recaptcha'><script src='https://www.google.com/recaptcha/api.js'></script>
<div class='g-recaptcha' data-sitekey='6LeLiLAUAAAAAFDTYsCggjTNNaGB4ETiakxsb9v6'></div>
<noscript>
  <div>
  <div style="width: 302px; height: 422px; position: relative;">
  <div style="width: 302px; height: 422px; position: absolute;">
  <iframe src="https://www.google.com/recaptcha/api/fallback?k=6LeLiLAUAAAAAFDTYsCggjTNNaGB4ETiakxsb9v6" frameborder="0" scrolling="no"
    style="width: 302px; height:422px; border-style: none;">
  </iframe>
  </div>
  </div>
  <div style="width: 300px; height: 60px; border-style: none; bottom: 12px; left: 25px; margin: 0px; padding: 0px; right: 25px; background: #f9f9f9; border: 1px solid #c1c1c1; border-radius: 3px;">
    <textarea id="g-recaptcha-response" name="g-recaptcha-response" class="g-recaptcha-response"
      style="width: 250px; height: 40px; border: 1px solid #c1c1c1; margin: 10px 25px; padding: 0px; resize: none;" >
    </textarea>
  </div>
  </div>
</noscript>
</div><input type=submit class="btn btn-info1" value=Submit aria-label="Submit button"></form>
