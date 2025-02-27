<h2>Desafio dio - Realizar Deploy na Nuvem de um Conjunto de API’s Desenvolvida em Spring Boot</h2>

<p>O objetivo dste desafio é criar um Sistema de Estacionamento para dar Entrada e Saída
dos Carros e emitir o valor da tarifa por hora.Nesta aplicação foi feito o deploy 
na plataforma Heroku. <a href="cloud-parking-acrani-dio.herokuapp.com/swagger-ui/index.html">Link da aplicação.</a></p> 

Vamos aplicar todas as boas práticas de desenvolvimento de API’s incluindo segurança com Spring Security e acesso a banco de dados PostgreSQL. Serão realizados testes e relatórios de cobertura de testes. Após finalizarmos a aplicação e termos enviado para o Github, vamos fazer o deploy na cloud do Heroku a fim de disponibilizar nossa API para a Internet.



<h2>Tecnologias Utilizadas</h2>
<p>- Java 17;</p>
<p>- Spring Boot;</p>
<p>- Spring Data;</p>
<p>- Spring REST;</p>
<p>- Spring SECURITY;</p>
<p>- Swagger;</p>
<p>- Database H2;</p>
<p>- Database Postgres;</p>
<p>- Heroku;</p>


<h2>Passo-a-Passo</h2>
<p>1. Criar as entidades;</p>
<p>2. Criar os repositories, services e controllers;</p>
<p>3. Implementar CRUD;</p>
<p>4. Implementar endpoints;</p>
<p>5. Implementar regras de negócio;</p>
<p>6. Implementar exception handles;</p>
<p>7. Swagger;</p>
<p>8. Implementar security;</p>


<h3>Material de apoio</h3>
<p><a href="https://github.com/sandrogiacom/cloud-parking">Link do material de apoio</a></p>



### Sequência Lógica de Trabalho:

1.  Apresentando a estrutura do pom.xml e as dependências do projeto.
2. Demonstrando outras formas de iniciar nosso projeto. Subindo a aplicação para GitHub.
3. Hospedando aplicação no Heroku. Adicionando o System Properties.
4. Apresentando os conceitos REST e Verbos HTTP. Criando o primeiro endpoint de cadastro.
5. Aplicando Design Patterns DTO para representar nossa view. Finalizando a criação do endpoint de cadastro.
6. Modelando a conversão das Lista e aplicando o o ResponseEntity.
7. Criando o método findById() e implementando o @PostMapping.
8. Documentando a API com Swagger utilizando o Spring Fox.
9. Configurando as exceções da aplicação e fazendo o tratamento no controller.
10. Construindo os métodos UPDATE e DELETE.
11. Realizando os testes da API e configurando as portas da aplicação.
12. Implementando os testes do findAll().
13. Revisando a API e iniciando o conceito de Persistência.
14. Trabalhando com JPA. Configurando o Banco de dados e criando um container.
15. Realizando alterações no Service e criando a interface Repository.
16. Implementando algoritmos da regra de negócio. Realizando o cálculo de dias e horas.
17. Testando o banco de dados da aplicação e realizando as implementações do TestContainers.
18. Atualizando as tabelas do banco de dados e visualizando o Heroku com o DB.
19. Configurando a segurança da aplicação, acessando e configurando acesso ao Swagger-uri. Adicionando a dependência Spring Security.
20. Criando a classe de configuração. Security web. SecurityConfiguration.
21. Finalizando as configurações de acesso e a API.
22. Entendendo o Desafio e Materiais de Apoio



### Finalizando as configurações de acesso e a API.

Entendendo o Desafio e Materiais de Apoio
