> *Anotações da Formação em Engenharia de Software da Alura.*

<h1 align="center">
  API e REST

###

![image](https://github.com/AndreCoutinhom/api_rest_study/assets/91290799/777dae18-df07-488c-bd13-a619791eafc8)

</h1>

A computação no geral é muito dinâmica e evolue em um ritmo bastante acelerado. Na engenharia de software não poderia ser diferente.  

Hoje em dia é bem comum a utilização de APIs que seguem o modelo REST no desenvolvimento de aplicações multiplataforma, sendo muito importante entender sobre tais assuntos.

## O que é uma API (*Application Programming Interface*)?

![image](https://github.com/AndreCoutinhom/api_rest_study/assets/91290799/4f3e743f-4ffe-47cc-83ee-833989531c2d)


* É uma interface entre o que se deseja e como realizar o que se deseja.

### Tipos de API
* APIs web: Requisições HTTP de diferentes serviços aplicáveis em sistemas de programação.
   
![image](https://github.com/AndreCoutinhom/api_rest_study/assets/91290799/decc66f8-ce7f-40e9-8ce0-48023dccd504)

  #### Padrões de API Web:
  *
    * RPC: Remote Procedure Call. Uma forma de chamar funções em URLs.
    * Soap: Fornecia protocolos para o uso de RPC através de funções XML (praticamente descartado hoje em dia).
    * REST: Padrão de APIs para requisição de conteúdos em HTTP em forma de métodos GET, POST, PUT, DELETE, etc (mais utilizado hoje em dia).

* APIs de código fonte: objetos utilizados em linguagens de programação para adquirir atributos de código. A sintaxe da API pode ser diferente dependendo da linguagem da programação.

## O que é REST

* Representational State Transfer, abreviado como REST, não é uma tecnologia, uma biblioteca, e nem tampouco uma arquitetura, mas sim um modelo a ser utilizado para se projetar arquiteturas de software distribuído, baseadas em comunicação via rede.
* REST é um dos modelos de arquitetura que foi descrito por Roy Fielding, um dos principais criadores do protocolo HTTP, em sua tese de doutorado e que foi adotado como o modelo a ser utilizado na evolução da arquitetura do protocolo HTTP.
* Inventado por **Roy Fielding**.
* A comunicação de aplicações ocorre entre clientes e servidores.
* O servidor não deve guardar dados de conexões ativas de clientes (sem cookies).
> *Cookies armazenam dados de acesso. Plataformas são capazes de registrar a atividade de clientes dentro da plataforma*.
* JWT (Json Web Token) permite que o servidor possa atribuir um token de identificação para cada cliente sem armazenar estados.
* Recursos identificáveis via URLs.
* Recursos são adquiridos por envio de representações, geralmente no formato JSON.
* Seguido pela semântica de verbos HTTP (GET, POST, PUT, DELETE, etc).
* Hypermedia é um termo utilizado para se referir a quantidade de dados retornados pelo servidor. Torna a leitura de URL mais simplificada e mais adequada ao consumidor final.

### Material de apoio:
* [Dissertação de Doutorado do Roy Fielding que descreve o REST](/architectural_styles_and_the_design_of_network_based_software_architectures.pdf)
* [REST APIs devem ser orientadas a hipertexto](https://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven)
* [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)
* [Postman](https://www.postman.com)

## [REST: Conceito e fundamentos](https://www.alura.com.br/artigos/rest-conceito-e-fundamentos?_gl=1*1l5jqb3*_ga*ODM1Nzk2OTUyLjE2OTgzNDc1Mjk.*_ga_1EPWSW3PCS*MTcwMzAyMzMwOC4xMDIuMC4xNzAzMDIzMzA4LjAuMC4w*_fplc*NVUzUzlBYVhTREVxS3ZJR1V1VkNneEFoSFJqZmVDeVU3dXYlMkJ5WE9tb2lvcmNnV0F4akdScjJzeTFUcmVEZnhiSXpmaE5FM0N3T0cxZjUyZk0lMkJiYnBrSzBBYjhyMktFR1ZvNWNQQWZIcHl6OGVLMW91d2FEQUxFdHA5ZDB1QSUzRCUzRA..)

## Boas práticas na Modelagem de API'S REST
