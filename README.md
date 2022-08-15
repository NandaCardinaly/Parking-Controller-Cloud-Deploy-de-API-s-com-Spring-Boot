### **Realizando Deploy na Nuvem de um conjunto de API’s desenvolvida em Spring Boot**  :computer: 


-------------------------------------------------------------------


#### Objetivo

Neste projeto foi desenvolveido um conjunto de API’s utilizando Spring Boot 
para controlar um estacionamento de veículos. Foram controlados a entrada, saída e valor a ser 
cobrado do cliente. Foram aplicadas todas as boas práticas de desenvolvimento de API’s incluindo 
segurança com Spring Security e acesso a banco de dados PostgreSQL. Foram realizados testes e 
relatórios de cobertura de testes. A aplicação foi finalizada e o deploy foi feito na cloud do 
Heroku a fim de disponibilizar a API para a Internet.



COMO FOI FEITO :notebook:

---------

- Criação do projeto utilizando o Spring Initializr, com a dependência Spring Web
- Criação da aplicação no Heroku, conectar ao GitHub e habilitar deploy automático
- Criação de Endpoints de cadastro (Model e Service)
- Implementação dos códigos de retorno HTTP de acordo com a operação
- Implementação e configuração do Swagger-UI para disponibilizar para o front-end
- Tratamento de exceções 
- Implementação de Testes automatizados de API
- Implementação das dependências maven e banco de dados
- Preparação da Entidade Parking
- Iniciação do container do banco de dados (Docker)
- Configuração do Spring Data JPA e criando a tabela no banco de dados
- Criação da interface repository
- Implementação dos códigos da regra de negócio e realização do cálculo de dias e horas
- Teste de todos os métodos via swagger
- Inclusão de transação
- Configuração do Heroku
- Configuração de segurança - adicionar dependência Spring Security
- Criação da classe de configuração
- Tornando API pública




---------

SOBRE A AUTORIA DO CÓDIGO :woman_technologist:

----------------

Agradecimentos ao professor que me instruiu nesse projeto:
[Sandro Giacomozzi](https://github.com/sandrogiacom)

**Fernanda Cardinaly** 

Técnica em Sistemas de informação  | Estudante de Engenharia da Computação

:business_suit_levitating: https://www.linkedin.com/in/fernandacardinaly

:cat: https://github.com/NandaCardinaly



