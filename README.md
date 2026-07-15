# Catálogo Digital KLAUS — site público

Este repositório contém **apenas o site já pronto** (HTML estático + fotos), gerado a partir do
sistema de planilha que fica na pasta `grade de produtos` (ou em `Z:\MARKETING 25\Sistema Novo`).
Ele existe separado daquele repositório de propósito, porque este aqui é feito pra ser público
(hospedado no Vercel), enquanto o outro guarda a planilha e as fotos de forma privada.

## Como atualizar o site publicado

1. Edite a planilha `Grade de Produtos.xlsx` normalmente (na pasta de trabalho de sempre).
2. Rode `Abrir Catalogo.bat` (ou só `Gerar_Catalogo.ps1`) pra gerar o `catalogo.html` atualizado.
3. Copie o `catalogo.html` gerado pra esta pasta, renomeando pra `index.html`.
4. Se adicionou fotos novas, copie também pra pasta `fotos/` aqui.
5. `git add`, `git commit` e `git push` — o Vercel republica o site sozinho a cada push.

## Aviso importante

O campo de usuário/senha do catálogo **não é uma proteção de verdade** — é só uma barreira simples.
Como este repositório fica público no GitHub e o site é acessível por qualquer pessoa com o link,
os dados (preços, fotos, especificações) não devem ser tratados como confidenciais depois de
publicados aqui.
