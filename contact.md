---
layout: default
---

<form id="contact-form" target="_self" method="post" action="URL_DO_SEU_BACKEND">
    <input required placeholder="nome" type="text" name="name"><br/>
    <input required placeholder="e-mail" type="email" name="email"><br/>
    <input required placeholder="assunto" type="text" name="subject"><br/>
    <textarea required 
        maxlength="2500" 
        placeholder="mensagem" 
        name="message" 
        rows='20'>
    </textarea><br/>
    <input type="submit">
</form>
