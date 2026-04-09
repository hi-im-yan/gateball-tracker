# Gateball Tracker

Placar offline para torneios de gateball. Um único arquivo HTML, sem servidor, sem internet.

## Como usar

1. Abra `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).
2. Digite o nome do torneio no topo.
3. Adicione partidas pelo formulário. A classificação atualiza automaticamente.
4. Clique em **Tela Cheia** e conecte o HDMI para exibir no telão (só a tabela de classificação aparece no modo telão).
5. Os dados ficam salvos automaticamente no navegador (localStorage).

## Backup dos dados

- **Exportar JSON**: baixa um arquivo `.json` com o torneio atual. Guarde como backup.
- **Importar JSON**: carrega um arquivo `.json` previamente exportado e substitui o estado atual.
- **Novo Torneio**: apaga tudo e começa do zero (pede confirmação).

## Requisitos

- Qualquer navegador moderno. Nenhuma conexão de internet é necessária.
- Para o modo telão funcionar bem, a resolução da TV precisa suportar fullscreen do navegador (F11 também funciona).

## Atenção

Os dados ficam no `localStorage` do navegador. Se você limpar o cache/dados do navegador, o torneio atual será perdido. **Exporte o JSON antes de encerrar** para ter um backup seguro.

## Arquivos

- `index.html` — o aplicativo inteiro (HTML + CSS + JS em um só arquivo)
- `sample-tournament.json` — exemplo para testar a importação
