<table>
  </tr>
    <td><h1>Sistema de Pedidos</h1></td>
  </tr>
</table>


## Conteúdo
* [Sobre a aplicação](#sobre-a-aplicação)
* [Status](#status)
* [Tecnologias](#hammer_and_wrench-tecnologias)
* [Iniciando a Aplicação](#car-Iniciando-a-aplicação)


## Sobre a aplicação

A aplicação permitiria lançar pedidos no celular e fechar os pedidos na aplicação web. Os pedidos podem estar na situação Aguardando, Em preparação ou Finalizado.<br />
O backend armazena os dados em um banco de dados __MongoDb__ e iria interagir com o front-end por meio de __WebSockets__.<br/>

## Status

Em produçâo, por ser um projeto vizando avaliaçâo não houve tempo habil para a conclusao do mesmo.


## :hammer_and_wrench: Tecnologias
* Back-end
  * __Node__ + __Express__ + __Typescript__
  * __Multer__ para upload de imagens
  * __Docker__ para criação de container para banco de dados
  * __Mongoose__ + __MongoDb__ para banco de dados
* Front-end
  * __React__ + __Vite__ + __Typescript__
  * __Styled-Components__ para estilização
<br />

## :car: Iniciando a aplicação
Baixe o repositório com git clone e entre na pasta do projeto.<br/>

```bash
$ git clone https://github.com/R1chardvieira/Sistema-pedidos
```
* Back-end
```bash
$ cd api
$ yarn
$ yarn dev
```
* Front-end
```bash
$ cd ..
$ cd web
$ yarn
$ yarn dev
```
