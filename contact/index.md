---
layout: page
title: Consultório
tags: [Consultório, Agendamento, psicóloga, Consulta, Atendimento, Localização]
date: 2019-03-29
comments: false
---

![Foto](../assets/img/content/consultorio/consultorio_1.jpg)  

## Áreas de atendimento

* Relacionamento
* Ansiedade
* Depressão
* Transtorno ou Síndrome de Pânico
* Transtorno Bipolar
* Fobia
* Sexualidade
* Falar em público
* Talentos, pontos fortes
* TOC - Transtorno Obsessivo-Compulsivo
* TEI - Transtorno Explosivo Intermitente
* TAG - Transtorno de Ansiedade Generalizada
* TEPT - Transtorno de Estresse Pós-traumático
* Outros atendimentos

---

{% comment %}
[Exemplo de link formato button]( {{ site.url }} ){: .btn}
{% endcomment %}

[//]: [Exemplo de link formato button]( {{ site.url }} ){: .btn}

## Informações para contato

<img style="width: 20px; height: 18px;float: left;" src="{{ site.url }}/favicon-psicologia-50x50.png">&nbsp;Psicóloga: Karynne Bayer

<i class="fas fa-brain fa-lg"></i> CRP: 05/37617

<i class="fab fa-whatsapp fa-lg"></i> Tel/WhatsApp: {{site.mobile}}

<i class="fas fa-envelope fa-lg"></i> E-mail: {{ site.email }}

<i class="fas fa-map-marker-alt fa-lg"></i> Endereço: **Office Tower** - Av. Evandro Lins e Silva, 840 / 7º Andar, Sala 715 - Barra da Tijuca, Rio de Janeiro

---

## Espaço terapêutico

{% capture images %}
    ../assets/img/content/consultorio/consultorio_1.jpg
    {% comment %}../assets/img/content/consultorio/consultorio_2.jpg{% endcomment %}
    ../assets/img/content/consultorio/consultorio_3.jpg
    ../assets/img/content/consultorio/consultorio_4.jpg
    {% comment %}../assets/img/content/consultorio/consultorio_5.jpg{% endcomment %}
    ../assets/img/content/consultorio/consultorio_6.jpg
    ../assets/img/content/consultorio/consultorio_7.jpg
    ../assets/img/content/consultorio/consultorio_8.jpg
{% endcapture %}
<div style="text-align: center;">{% include gallery images=images caption="Marque sua consulta!" cols=2 %}</div>

---

## Localização

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d486.36577377518364!2d-43.32650881377901!3d-23.003743731981494!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9bd0a6cce79395%3A0x187f417d257fc2b3!2sOffice+Tower!5e0!3m2!1spt-BR!2sbr!4v1554051902313!5m2!1spt-BR!2sbr" width="100%" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

---

## Contato

<p>Caso tenha alguma dúvida, sugestão ou prefira marcar sua consulta por aqui, deixe sua mensagem. Será um prazer atendê-lo.</p>

<form method="post" action="https://formspree.io/{{ site.email }}">
  <div class="row">
    <div class="6u 12u$(mobile)"><input type="text" name="Nome" placeholder="Nome completo: " /></div>
    <div class="6u$ 12u$(mobile)"><input type="text" name="Email" placeholder="Email: " /></div>
    <div class="12u$">
      <textarea name="Mensagem" placeholder="Mensagem"></textarea>
    </div>
    <div class="12u$">
      <input type="submit" value="Enviar mensagem" />
    </div>
  </div>
</form>