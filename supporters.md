---
layout: default
title: Patrocinadores
---

# {{ page.title }}


As empresas interessadas em colaborar para o patrocínio do 17º Congresso Nacional de Geotecnia e do
10º Congresso Luso-Brasileiro de Geotecnia podem fazê-lo de várias formas, conforme os quadros abaixo.
Para mais informações não deixe de [contactar a Organização](contacts.html) através de um dos diversos contactos
disponibilizados. 

<br>
<p>
<div class="ui-corner-all custom-corners">
<div class="ui-bar ui-bar-a" markdown="1">
### Platina (6000 Euros)
</div>

<div class="ui-body ui-body-a" markdown="1">
- 8 Inscrições de participante;
- Logótipo no 2º e 3º boletim (*);
- Logótipo no website do evento (*);
- Logótipo no CD-ROM das atas do evento (*);
- Logótipo no livro de resumos (*);
- Logótipo no programa final (*);
- Logótipo e link do website da empresa no website do evento (*);
- Folheto informativo e ou CD-Rom da empresa incluído nas pastas a distribuir aos participantes;
- Projeção de publicidade da empresa nos intervalos das sessões (*).

<small> (*) Logótipo com dimensão maior que o logótipo do patrocinador "Ouro" </small>

<!-- Current Sponsors: -->

<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "platinum"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 100px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</div>
</div>

</p>


<p>
<div class="ui-corner-all custom-corners">
<div class="ui-bar ui-bar-a" markdown="1">
### Ouro (4000 Euros)
</div>

<div class="ui-body ui-body-a" markdown="1">
- 5 Inscrições de participante;
- Logótipo no 2º e 3º boletim (*);
- Logótipo no website do evento (*);
- Logótipo no CD-ROM das atas do evento (*);
- Logótipo no livro de resumos (*);
- Logótipo no programa final (*);
- Logótipo e link do website da empresa no website do evento (*);
- Projeção de publicidade da empresa nos intervalos das sessões (*).

<small> (*) Logótipo com dimensão maior que o logótipo do patrocinador "Prata" </small>

<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "gold"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 90px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</div>
</div>

</p>

<!-- Current Sponsors: -->

<p>
<div class="ui-corner-all custom-corners">
<div class="ui-bar ui-bar-a" markdown="1">



### Prata (2000 Euros)

</div>

<div class="ui-body ui-body-a" markdown="1">
- 2 Inscrições de participante;
- Logótipo no 2º e 3º boletim (*);
- Logótipo no website do evento (*);
- Logótipo no CD-ROM das atas do evento (*);
- Logótipo no livro de resumos (*);
- Logótipo no programa final (*);
- Logótipo e link do website da empresa no website do evento (*);
- Projeção de publicidade da empresa nos intervalos das sessões (*).

<small> (*) Logótipo com dimensão maior que o logótipo do patrocinador "Bronze" </small>


<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "silver"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 90px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</div>
</div>

</p>

<!-- Current Sponsors: -->

<p>
<div class="ui-corner-all custom-corners">
<div class="ui-bar ui-bar-a" markdown="1">



### Bronze (1000 Euros)

</div>

<div class="ui-body ui-body-a" markdown="1">
- 1 Inscrições de participante;
- Logótipo no 2º e 3º boletim (*);
- Logótipo no website do evento (*);
- Logótipo no CD-ROM das atas do evento (*);
- Logótipo no livro de resumos (*);
- Logótipo no programa final (*);
- Logótipo e link do website da empresa no website do evento (*);
- Projeção de publicidade da empresa nos intervalos das sessões (*).

<small> (*) Logótipo com dimensão menor que o logótipo do patrocinador "Prata" </small>

<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "bronze"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 90px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</div>
</div>

</p>

