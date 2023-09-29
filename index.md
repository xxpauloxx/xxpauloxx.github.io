---
layout: default
title: Hello, World!
---

{% capture current_lang %}{{ site.lang | default: "en" }}{% endcapture %}
<h2>{{ site.data[current_lang].hello }}</h2>

<button onclick="changeLanguage('en')">English</button>
<button onclick="changeLanguage('pt')">Português</button>

<script>
function changeLanguage(lang) {
    document.querySelector('h2').textContent = site.data[lang].hello;
}
</script>
Agora, com esses botões, você pode alternar entre os idiomas inglês e português clicando nos botões "English" e "Português". Certifique-se de ter os arquivos de tradução _data/en.yml e _data/pt.yml configurados corretamente com as traduções adequadas.

Após fazer essas alterações, faça o commit e envie novamente os arquivos para o repositório do GitHub e aguarde a atualização no GitHub Pages. Depois de concluído, você deve ser capaz de alternar entre os idiomas ao clicar nos botões.






