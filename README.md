# Blog do cinco atelier (Jekyll)

## Como instalar
1. Copie o conteúdo desta pasta para a raiz do repositório do site (não apague nem substitua o index.html, o questionario.html nem o analiseplanta.html).
2. Abra `_config.yml` e troque `SEU_UTILIZADOR` pelo utilizador do Instagram.
3. Faça commit e push. O GitHub Pages compila o Jekyll sozinho.
4. O blog fica em `/blog.html`. Adicione um link "Blog" ao menu do site.

## Como publicar um artigo
Crie um ficheiro em `_posts/` com o nome `AAAA-MM-DD-titulo-do-artigo.md`:

---
layout: post
title: "Título do artigo"
date: 2026-11-10 09:00:00 +0000
resumo: "Frase curta que aparece na lista do blog."
instagram: https://www.instagram.com/p/CODIGO/   (opcional)
---
Texto do artigo em Markdown.

## Instagram
- Botão para o perfil: já incluído no fim do blog e no topo.
- Feed automático: cole o código do widget em `_includes/instagram-feed.html`.
- Publicação concreta num artigo: use `instagram:` no cabeçalho do artigo.
