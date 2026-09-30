# Checklist Novo Gestor

Acompanhamento, relatório a relatório, do que os clientes pedem no sistema Gestor. As solicitações vêm das pesquisas feitas pelo time de Product Design no Tally (pasta Pesquisa Novo Gestor, respostas de 21 a 30/09/2026).

## O que é

Página única (`index.html`), sem dependências de build, com uma aba por pesquisa/relatório. Cada aba traz um checklist do que não pode faltar, com busca, filtro por categoria e por status, número de menções e clientes que pediram.

## Como usar

- Abra o `index.html` no navegador ou publique pelo GitHub Pages.
- Marque cada item conforme o andamento. As marcações ficam salvas no navegador de cada pessoa (localStorage) e continuam marcadas ao fechar e reabrir a página.
- Limpar os dados do navegador ou abrir a página em outro navegador ou endereço apaga as marcações.

## Publicar no GitHub Pages

1. Suba `index.html` e `README.md` na raiz do repositório.
2. Em Settings, Pages, escolha a branch `main` e a pasta `/ (root)`.
3. O site fica em `https://<organização>.github.io/<repositório>/`.

## Atenção

A página lista nomes de clientes e o que eles disseram. Em repositório público, o conteúdo fica aberto a qualquer pessoa com o link.

## Atualizar os dados

Os itens ficam no bloco `DATA` dentro do `index.html`. Cada item segue o formato `[categoria, requisito, detalhe, [clientes], origem opcional]`. Não reordene nem apague itens de uma pesquisa já em uso: as marcações são guardadas pela posição do item no bloco.
