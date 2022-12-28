# 209_PersonalizandoAcessosAutomatizandoAcoesMySQL
Personalizando Acessos e Automatizando ações no MySQL



[**](https://web.dio.me/track/formacao-sql-db-specialist)

##### Personalizando Acessos e Automatizando ações no MySQL

**

[**](https://web.dio.me/lab/personalizando-acessos-e-automatizando-acoes-no-mysql/learning/62eaff59-492c-456e-9479-33f9f252cd34)[**](https://web.dio.me/lab/personalizando-acessos-e-automatizando-acoes-no-mysql/learning/593522c7-e2a2-4fbd-b9da-e5f7d42de408)

<iframe id="ytc20" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" title="Personalizando Acessos e Automatizando ações no MySQL - parte 1" width="100%" height="100%" src="https://www.youtube.com/embed/gle1gK3CA9Y?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-16="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:10

 

03:46







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Personalizando Acessos e Automatizando ações no MySQL - parte 1](https://web.dio.me/lab/personalizando-acessos-e-automatizando-acoes-no-mysql/learning/62eaff59-492c-456e-9479-33f9f252cd34)[Personalizando Acessos e Automatizando ações no MySQL - Parte 2](https://web.dio.me/lab/personalizando-acessos-e-automatizando-acoes-no-mysql/learning/593522c7-e2a2-4fbd-b9da-e5f7d42de408)[Entendendo o desafio](https://web.dio.me/lab/personalizando-acessos-e-automatizando-acoes-no-mysql/learning/5fe40d04-7d5e-4854-b551-61d06cac7519)





**Parte 1 – Personalizando acessos com views** 

Neste desafio você irá criar visões para os seguintes cenários 

- Número de empregados por departamento e localidade 
- Lista de departamentos e seus gerentes 
- Projetos com maior número de empregados (ex: por ordenação desc) 
- Lista de projetos, departamentos e gerentes 
- Quais empregados possuem dependentes e se são gerentes 

 

Além disso, serão definidas as permissões de acesso as views de acordo com o tipo de conta de usuários. Lembre-se que as views ficam armazaneadas no banco de dados como uma “tabela”. Assim podemos definir permissão de acesso a este item do banco de dados. 

 

Você poderá criar um usuário gerente que terá acesso as informações de employee e departamento. Contudo, employee não terá acesso as informações relacionadas aos departamentos ou gerentes. 

Um exemplo retirado da aula para criação de usuário e definição de permissão pode ser encontrado abaixo. 

CODE 1:



Obs: O tema de permissão de usuários foi apresentada no curso Explorando Cláusulas de DDL e Esquemas de Banco de Dados no MySQL. 

 

**Parte 2 – Criando gatilhos para cenário de e-commerce** 

Objetivo: 

Sabemos que a criação de triggers está associadas a ações que podem ser tomadas em momento anterior ou posterior a inserção, ou atualização dos dados. Além disso, em casos de remoção podemos utilizar as triggers. Sendo assim, crie as seguintes triggers para o cenário de e-commerce. 

 

Exemplo de trigger para base.

CODE 2:



Entregável: 

- Triggers de remoção: before delete 
- Triggers de atualização: before update 

 

Remoção: 

Usuários podem excluir suas contas por algum motivo. Dessa forma, para não perder as informações sobre estes usuários, crie um gatilho before remove 

CODE 3:



Atualização: 

Inserção de novos colaboradores e atualização do salário base. 

CODE 4:



E agora... Finalizou seu desafio ? 

Adicione o link do github com o projeto e submeta para avaliação. 

 

- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO



**SQL**

------

###### Full-Stack

###### Avançado

------

###### ESPECIALISTA

![author](https://hermes.digitalinnovation.one/users/author/photos/a3d71bed-2938-4df8-95e1-3d4181cad1c3.png)

###### Juliana Mascarenhas

Data Scientist, DIO[**](https://www.linkedin.com/in/juliana-mascarenhas-00349426/)

