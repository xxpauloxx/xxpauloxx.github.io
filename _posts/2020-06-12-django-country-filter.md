---
layout:     post
title:      Middleware para filtrar requisições de países no Django
date:       2020-06-12 11:21:29
summary:    Middleware para filtrar requisições de países específicos no Django.
categories: django python geoip
---

Em alguns momentos você irá desenvolver aplicações que não necessita estar disponível para toda a Internet, ou seja, para outros países. Embora seja um situação muito especifica, pode acontecer. Algum tempo atrás desenvolvi um gerenciador de conteúdo para um sistema de educação a distância, devido aos problemas da pandemia, escolas municipais migraram suas aulas para a Internet.



Definimos que a plataforma não poderia ser acessada de fora do país, pra diminuir os problemas na qual deveriamos lidar no dia a dia. Pra quê ficar na mira de hackers adolescentes de outros países. Hehehe



Existem plataformas para fazer esse controle, mas por motivos particulares decidimos que o bloqueio seria feito diretamente no software via middleware. Como a aplicação que tinha desenvolvido era em Django, decidi desenvolver um middleware e disponibilizar o código para a comunidade.



A página do projeto é [https://github.com/xxpauloxx/django-country-filter](https://github.com/xxpauloxx/django-country-filter).



