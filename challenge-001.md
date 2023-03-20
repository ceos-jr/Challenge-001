# Desafio 001

Com a migração da Ceos para o desenvolvimento de sistemas, se faz necessário que
nós desenvolvamos os conhecimentos que são base para a construção desses
projetos.

Em resumo, o desafio consiste no desenvolvimento de uma aplicação que realiza
operações de leitura e escrita em um banco de dados, assim como o uso de uma API
e a integração dela ao "front-end"

## Tecnologias

- React
- CSS / Tailwind / outros
- Express
- Postgress (banco de dados)

## O problema

### Front end

Você deve desenvolver e estilizar uma página feita em **React**. A estilização e
a tecnologia utilizada será escolhida por você. A página deve conter um titulo e
duas seções:

- A primeira consiste em um formulário que o usuáro irá preencher e enviar os
  dados ao servidor.
- A segunda consiste em um campo em que o usuário solicitará os dados presentes
  no banco e os mesmos serão mostrados na tela.

O formulario contem os seguintes campos: Nome, idade, profissão e mensagem.

- Você pode utilizar o modelo do site da Ceos para se inspirar.
- Lembre-se de impedir que o usuário envie dados incompletos ao servidos.

### Back end

O backend da aplicação consiste em uma **API** escrita em **Express** que contêm
endpoints que tratam o input recebido pelo formulario preenchido pelo usuário e
salva esses dados no banco de dados. O outro endpoint tem como proposito extrair
os dados do banco de dados, envia-los ao front end e mostra-los na tela.

### Banco de dados

O banco de dados utilizado será o postgress, o qual utiliza a linguagem SQL.
Crie tabelas no banco para armazenar os dados vindos do backend.

## Avaliação

O intuito desse desafio é o aprendizado, porém, faremos uma avaliação do código.
A avaliação consiste em apontar erros feitos e pontos que podem ser melhorados.

## Duvidas

Caso tenha alguma dúvida em relação ao desafio, não exite em perguntar e
pesquisar na internet. Lembre-se, todos estamos aqui para aprender.

## Referencias

Vou anexar alguns videos e artigos que serão uteis na execução do desafio.

- [Curso de React](https://www.youtube.com/watch?v=bMknfKXIFA8)
- [Curso de Postgress](https://www.youtube.com/watch?v=qw--VYLpxG4)
- [Curso de Express](https://www.youtube.com/watch?v=Oe421EPjeBE&t=104s)

Esses cursos que eu linkei são bem completos. Os três cursos tem timestamp para
você assistir as partes mais relevantes.

- [Docs do Express](https://expressjs.com/)
- [Docs do React](https://react.dev/)
- [Docs do Postgress](https://www.postgresql.org/docs/current/)

Essas são as documentações oficiais das ferramentas que utilizaremos no desafio.
Um bom programador precisa saber ler a documentação de uma determinado
ferramenta, então eu aconselho você a tentar ler a documentação para ir se
acostumando com a estrutura delas.
