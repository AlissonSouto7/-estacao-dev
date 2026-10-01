# Estação Dev

Site estático: só HTML e um arquivo de conteúdo. Não tem servidor.

- `index.html` é o site.
- `conteudo.json` guarda as trilhas, módulos e aulas.
- O progresso de cada pessoa fica salvo no navegador dela.

## Editar o conteúdo (admin)

1. Abra o site com `?admin` no fim do endereço. Ex.: `https://estacao-dev.pages.dev/?admin`
2. Clique em **Editar conteúdo** e crie ou altere as trilhas.
3. Clique em **Baixar conteudo.json**.
4. No GitHub, substitua o `conteudo.json` do repositório pelo que você baixou.
5. Em cerca de 1 minuto o Cloudflare publica a nova versão para todo mundo.

Enquanto você não sobe o arquivo, as mudanças ficam só no seu navegador como rascunho.
