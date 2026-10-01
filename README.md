# estacao-dev

Trilha de estudos em estilo terminal. Site estático: `index.html` + `conteudo.json`.
O progresso de cada pessoa fica salvo no navegador dela.

## Comandos (todo mundo)

- `next` abre a próxima aula · `ok` conclui a aula aberta
- `open M/A` abre a aula A do módulo M · `cd N` troca de trilha · `ls` lista as trilhas
- `tree` / `fold` expande / recolhe · `player` liga/desliga o vídeo
- `neofetch` resumo · `achievements` conquistas · `nome seu_nome` muda o prompt
- `Tab` completa · `↑ ↓` histórico · `Ctrl+L` limpa

## Admin

Abra o site com `?admin` no fim do endereço e digite `help`.

- `add trilha NOME` · `add mod NOME` · `add aula M TÍTULO | URL`
- `edit trilha` · `edit mod M` · `edit aula M/A`
- `rm mod M` · `rm aula M/A` · `rm trilha`
- `mv mod M up|down` · `mv aula M/A up|down` · `mv trilha up|down`
- `import` cola uma lista (`# Módulo` e `Título | link | duração`)
- `export` baixa o `conteudo.json` · `discard` descarta o rascunho

Para publicar: `export`, depois substitua o `conteudo.json` no GitHub. O Cloudflare atualiza em ~1 minuto.