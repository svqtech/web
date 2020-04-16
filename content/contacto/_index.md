---
title: 'Contacto'
intro_image: images/fish.png
---

# ¿Quieres unirte a la metacomunidad?

## Contacta con nosotros para dejarnos tus sugerencias o peticiones

<form name="contact" action="/thank-you/" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div>
        <label for="Name"></label>
        <div>
            <input id="contact-form-name" name="Name" type="text" placeholder="Nombre" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div>
        <label for="Email"></label>
        <div>
            <input id="contact-form-email" name="Email" type="email" placeholder="Email de contacto" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div>
        <label for="Subject"></label>
        <div>
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Asunto" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div>
        <label for=""></label>
        <textarea id="contact-form-message" name="Message" placeholder="¿En qué podemos ayudarte?" rows="8"></textarea>
    </div>
    <!-- Button -->
    <div>
        <button type="submit" value="Submit" id="Form-submit">Enviar</button>
    </div>

</form>
