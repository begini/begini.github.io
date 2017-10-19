---
layout: page
title: Kontak
subtitle: kirim pesan ke pengelola
bigimg: "/img/big/contact.jpg"
css: '/css/form.css'
---

Silakan lengkapi form di bawah untuk mengirim pesan ke pengelola situs ini

<form method="POST" class="form" action="https://formspree.io/sompret@yandex.com">
  <input type="text" name="name" placeholder="Nama Lengkap" />
  <input type="email" name="_replyto" placeholder="Alamat Email" />
  <input type="hidden" name="_next" value="//begini.github.io/thanks" />
  <input type="text" name="_gotcha" style="display:none" />
  <input type="hidden" name="_subject" value="[begini] Form Kontak" />
  <input type="hidden" name="_format" value="plain" />
  <textarea name="message" placeholder="Isi Pesan"></textarea>
  <button type="submit">Kirim</button>
</form>
