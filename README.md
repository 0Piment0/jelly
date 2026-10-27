# Jelly Clips

Controle de clipes e vídeos em um único arquivo HTML. Não precisa instalar nada.

## Como usar

Abra o `index.html` no navegador. Para o player do YouTube funcionar dentro da página,
sirva por http (ex.: GitHub Pages ou `python3 -m http.server`). Aberto direto do disco,
o clipe abre no site original.

## O que faz

- Cadastro de clipes: título, link, plataforma, status, data, duração, tags, capa e notas
- Detecta a plataforma pelo link (YouTube, Twitch, TikTok, Instagram, Kick, X, Drive) e puxa a capa do YouTube sozinho
- Fluxo de status: Ideia → Gravado → Editando → Pronto → Publicado
- Visão em grade ou em quadro (arraste os cards entre as colunas)
- Busca, filtro por plataforma, status, tag e favoritos
- Backup em JSON (exportar e importar) e planilha CSV para o Excel
- Tema claro/escuro, funciona no celular
- Atalhos: `N` cria um clipe novo, `/` vai para a busca

## Atenção

Os dados ficam salvos **só no navegador onde a página foi aberta**. Trocar de aparelho,
de navegador ou limpar os dados do site apaga a lista. Faça backup pelo botão **Backup**.
