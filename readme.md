# Tarefa 33 - Página pessoal com DaisyUI

1. Componentes DaisyUI utilizados

Hero:

Foi utilizado no cabeçalho da página. Ele apresenta meu nome,
minha área de atuação e os botões de navegação.

Badge:

Foi utilizado na apresentação para mostrar algumas tecnologias
que estou aprendendo, como HTML, CSS e Python.

Card:

Foram utilizados três cards na seção de projetos.
Cada card possui card-body, título, descrição e botão de ação.

Button:

Foram utilizados vários botões na página.
Usei diferentes estilos, como btn-primary,
btn-secondary e btn-outline.

Input:

Os inputs foram utilizados no formulário de contato.
A página possui campos para nome e e-mail.

Data-theme:

Foi utilizado o data-theme para definir o tema da página.

2. Justificativa da escolha do Hero

Escolhi o hero em vez do navbar porque a página é uma
apresentação pessoal, e achei mais simples a utilização.

O Hero permitiu colocar meu nome, minha área e os botões
logo no início da página de uma forma simples.

3. Pontos de ajuste com Tailwind

Usei classes do Tailwind para organizar o conteúdo.

Uma delas foi:

html
grid grid-cols-1 md:grid-cols-3

Essa classe organiza os três cards. Em telas pequenas eles
ficam um embaixo do outro e em telas maiores ficam lado a lado.

Também utilizei classes como:

html
max-w-5xl mx-auto

para controlar a largura e centralizar o conteúdo.

4. Reflexão sobre os temas

A página foi configurada com o tema dark:

<html lang="pt-BR" data-theme="dark">


Também testei o tema light alterando para:

<html lang="pt-BR" data-theme="dark">

O tema dark ficou mais coerente com a proposta da página
porque deixou a página mais visualmente bonita, e deixou o conteúdo mais simples e fácil de visualizar.

Os dois temas funcionam corretamente porque os componentes
do DaisyUI utilizam as cores do tema automaticamente.
