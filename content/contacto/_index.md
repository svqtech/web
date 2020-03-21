---
title: 'Contacto'
intro_image: images/tree.png
---

Aquí va el formulario y los datos de contacto.

<form name="contact" action="/thank-you/" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div>
        <label for="Name"></label>
        <div>
            <input id="contact-form-name" name="Name" type="text" placeholder="Name" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div>
        <label for="Email"></label>
        <div>
            <input id="contact-form-email" name="Email" type="email" placeholder="Email Address" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div>
        <label for="Subject"></label>
        <div>
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Subject" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div>
        <label for=""></label>
        <textarea id="contact-form-message" name="Message" placeholder="What's up?" rows="8"></textarea>
    </div>
    <!-- Button -->
    <div>
        <button type="submit" value="Submit" id="Form-submit">Submit</button>
    </div>
</form>
